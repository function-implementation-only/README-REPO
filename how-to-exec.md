## 실행 방법

아래는 이 프로젝트를 실행하는 방법입니다.

### 0. 사전 준비

프로젝트를 실행하기 전에 다음과 같은 소프트웨어가 설치 및 준비 되어야 합니다 <br>
※버전정보가 다를 경우 실행을 보장 하지 않습니다

- Docker(version 20.10.20,)
- Docker Compose(version v2.12.0)
- MySQL(version 8.0.28)

### 1. Git clone

다음 명령어를 통해 git clone 합니다

### 2. Docker image 생성

프로젝트 루트 디렉토리에서 다음 명령어를 실행합니다

### 3. Docker image push

Docker hub를 통해 image를 push 합니다

### 4. Docker compose 파일 작성

프로젝트 루트 디렉토리에 있는 docker-joinus.yml 파일을 수정합니다

### 5. Docker network 생성

다음 명령어를 통해 Docker network를 생성합니다

### 6. Docker compose 실행

프로젝트 루트 디렉토리에서 



## 개발 환경

- 언어: Java (version 11)
- 프레임워크: Spring Boot(2.7.4)
- 데이터베이스: MySQL(version 8.0.28)

## 참고 자료

프로젝트와 관련된 자세한 내용은 아래 자료를 참고하십시오.

- [API 문서](http://localhost:[포트번호]/api-docs)
- [Swagger UI](http://localhost:[포트번호]/swagger-ui.html)
