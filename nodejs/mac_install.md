```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
```
* zshrc 등록하지 않으면
complete:13: command not found: compdef


#### 설치가 되면 ~/.bash_profile, ~/.zshrc, ~/.profile 등의 프로파일에 nvm.sh이 실행되도록 다음 스크립트가 추가됩니다.

```
vi ~/.bash_profile

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

# nvm 통해 node 설치하기
[site](https://medium.com/@moralmk/node-js-%EB%B2%84%EC%A0%84-%EA%B4%80%EB%A6%AC-%EB%B0%A9%EB%B2%95-84818ceeff08)
10.x 버전 중 가장 최신 버전의 node를 설치하는 명령입니다. 제거는 물론install 옵션 대신 uninstall 사용하면 됩니다.
$ nvm install 10
