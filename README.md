# Graduation-Hepler
졸업자격 체크리스트

1. [nodejs/npm 설치](https://velog.io/@loakick/AWS-EC2-Ubuntu-18.04%EC%97%90-NodeJS-Github-Mysql-%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0)



apt-get update
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
apt-get install -y nodejs

sudo curl -L https://npmjs.org/install.sh | sh


2. mongodb 설치
apt-get install mongodb

3.CLONE
git clone https://github.com/lee95292/Graduation-Hepler
cd Graduation-Hepler/

4.서버 및 클라이언트 패키지 설치.  

npm install  
cd frontend
npm install  

5.서버 클라이언트 실행
npm install nodemon -g
nodemon &  
cd client  
npm run start  


http://ipaddr:3000/main  접속
