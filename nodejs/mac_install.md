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
