# linux mint 19
기존 open sdk 10 가 설치 되어 있으므로 실행안됨

```
sudo add-apt-repository ppa:webupd8team/java
sudo apt update && sudo apt-get install oracle-java8-installer
```

* 에러발생 sudo update-alternatives --config java


# oracle jdk8 설치 안됨
https://www.oracle.com/technetwork/java/javase/downloads/index.html

sudo tar xfz jdk-8u231-linux-x64.tar.gz -C /opt/

echo 'export JAVA_HOME=/opt/jdk1.8.0_231/' | sudo tee /etc/profile.d/java.sh

echo 'export PATH=$PATH:/opt/jdk1.8.0_231/bin' | sudo tee -a /etc/profile.d/java.sh

sudo update-alternatives --config java
* There is only one alternative in link group java (providing /usr/bin/java): /usr/lib/jvm/java-11-openjdk-amd64/bin/java


# openjdk-8-jdk 설치
sudo apt-get install openjdk-8-jdK
sudo update-alternatives --config java
