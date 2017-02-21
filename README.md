## Thrift JS PoC Project

Thrift RPC 시스템을 이용하여 서버와 통신하는 모습을 보여주기 위해 만든 자바스크립트 클라이언트 데모 프로젝트입니다. 

### 1. 프로젝트 설치

프로젝트를 복제합니다.

```bash
$ git clone git@github.com:appkr/thrift-js-poc-project.git

# or 

$ git clone https://github.com/appkr/thrift-js-poc-project.git 
```

의존성을 설치합니다.

```bash
~/thrift-js-poc-project $ npm install

# or

~/thrift-js-poc-project $ yarn insall
```

웹 서버를 구동하고 브라우저에서 확인합니다.

```bash
~/thrift-js-poc-project $ php -S localhost:8888

# or

~/thrift-js-poc-project $ http-server -p 8888
```

### 2. 서버

이 프로젝트의 요청을 처리할 수 있는 서버 프로젝트는 https://github.com/appkr/thrift-example-project 에서 확인할 수 있습니다.

