1.리눅스 버전확인
# cat /etc/*-release | uniq
CentOS Linux release 7.3.1611 (Core)

2. repl 저장소 설치
# yum install epel-release

3. node.js npm 설치
# yum install npm nodejs
4. 최신버전 업데이트 (버전관리자 사용)
# yum update openssl
# npm cache clean -f
# npm install -g n

** 특정버전 설치시
# n 6.11.0

** 최신 안정화 버전 설치시
# n stable

** 가장 최신버전 설치시
# n latest
