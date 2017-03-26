# README

## 環境
ruby 2.3.0  
rails 5.0.0  
mysql 5.7  
redis 3.2  
nginx 1.11.10  

## docker
rails  
mysql  
redis  
nginx  

## 環境構築
```
$ git clone https://github.com/ikotan/rails5app-angular2-template.git
$ cd rails5api-angular2-template/
```

```
$ docker-compose build
$ docker-compose up
$ docker-compose exec rails rails db:create
```

```
$ front/
$ npm install
$ npm start
```

