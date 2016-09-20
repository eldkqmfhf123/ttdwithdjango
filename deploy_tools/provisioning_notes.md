신규 사이트 프로비저닝

## 필요 패키지

* nginx
* Python 3
* Git
* pip
* virtualenv

sudo apt-get install nginx git python3 python3-pip
sudo pip3 install virtualenv

## nginx 가상 호스트 설정

* nginx.template.conf 참고

## Upstart Job

* gunicorn-upstart.template.conf 참고

## 폴더 구조:
사용자 계정의 홈폴더가 /home/skriex라고 가정

/home/skriex
 - sites
	- staging.skriex.com
		- database
		- source
		- static
		- virtualenv 
