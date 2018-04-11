# Fastcampus

# 커리큘럼
> 정해진 커리큘럼이 아닌, 제가 생각 중인 강의 방식을 간략히 적어두었습니다.
> 추후 논의가 필요합니다.
> 8주차(한 주 4시간) 기준으로 작성되었습니다.

- 1주차
  - *Javascript, Node.js*의 구동 방식에 대한 설명 - **1 hour**
    - Function language에 대한 간단한 개요
    - Node.js V8 Engine(Chrome browser engine을 왜 가져다 썼을까?) - **Event loop**의 장단점
    - Typescript 간단히 보기
  - *서버 아키텍처* 비교 - **1 hour**
    - 모노리틱(기존에 많고 많았던...) 아키텍처
    - 서버리스(진짜 서버가 없을까?) 아키텍처
    - **마이크로 서비스 아키텍처**
  - *Docker 맛보기 (Docker hub를 통해 오픈소스 설치해보기)* - **1 hour**
    - Nginx 웹서버 설치(8080:80 포트 매핑)
    - MySQL 설치(기본 설정 및 MySQL client tool 연결)
  - NPM(Node package manager)을 통해 Node.js(v8.11.1 LTS) 설치해보기 - **1hour**
    - NPM vs Yarn
    - what is package.json?
    - 프로젝트 구성에 대한 **Best practice**
- 2주차
  - *Node.js, Express(Web framework), Knexjs(Query builder)을 통해 간단한 CRUD Api 작성해보기* - **4hour**
    - 데이터 요청/응답 REST Api
    - JWT(Json web token) 인증/인가 서비스
    - Email push 서비스
    - Postman, Rest client, swagger 등 Api docs를 만들고 테스트