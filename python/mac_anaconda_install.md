
# 유저 전환
source activate dhshin

# 삭제
```
rm -rf ~/anaconda3 ~/.conda ~/.anaconda ~/.condarc
rm ~/Library/Application Support/binstar/*anaconda*
rm ~/Library/Receipts/io.continuum.pkg.anaconda*
rm ~/opt/anaconda*
```




# Anaconda를 사용하여 전체 제거 - 깨끗하고 간단한 제거. --안씀

참고 : 간단한 제거 전에 Anaconda-Clean을 실행해야합니다.

Anaconda-Prompt 또는 터미널 창에서 Anaconda-Clean 패키지를 설치하십시오.

conda install anaconda-clean
동일한 창에서 다음 명령 중 하나를 실행하십시오.

각 파일을 삭제하기 전에 모든 아나콘다 관련 파일 및 디렉토리를 확인하라는 메시지가 나타나면 제거하십시오.

anaconda-clean
또는 각 파일을 삭제하라는 메시지를 표시하지 않고 모든 Anaconda 관련 파일 및 디렉토리를 제거하십시오.

anaconda-clean --yes
Anaconda-Clean은 홈 디렉토리의 .anaconda_backup 폴더에서 .bash_profile 과 같이 제거 될 수있는 모든 파일 및 디렉토리의 백업을 만듭니다. 또한 Anaconda-Clean은 AnacondaProjects 디렉토리의 데이터 파일을 변경하지 않습니다. Anaconda-Clean을 사용한 후에 옵션 A의 위 지침에 따라 Anaconda를 제거하십시오. .bash_profile 에서 Anaconda 경로 제거하기

Linux 또는 macOS를 사용하는 경우 홈 디렉토리의 .bash_profile 파일에서 다음과 같은 행을 확인할 수도 있습니다.

export PATH="/Users/jsmith/anaconda3/bin:$PATH"
참고 : /Users/jsmith/anaconda3/ 을 실제 경로로 바꿉니다.

이 행은 Anaconda 경로를 PATH 환경 변수에 추가합니다. 아나콘다 또는 미니콘다를 지칭 할 수 있습니다. Anaconda를 제거한 후이 줄을 삭제하고 파일을 저장할 수 있습니다.

https://docs.anaconda.com/anaconda/install/uninstall
