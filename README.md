# Fastcampus

# 커리큘럼
<!-- > 정해진 커리큘럼이 아닌, 제가 생각 중인 강의 방식을 간략히 적어두었습니다.
> 추후 논의가 필요합니다. -->
> 6주차(한 주 4시간) 기준으로 작성되었습니다. 개념 정립 -> 실습 단계가 아닌 실습 이후 개념 설명을 기본 과정으로 생각하고 있습니다. ```ex) 먼저 Nginx 구축, 운영을 해보고 웹서버를 띄우고 운영하는 이유에 대한 개념 설명```

- 1주차 `웹 서버 구축` - 4hour
  - 테스트

<!-- - 1주차
  - *Javascript, Node.js*의 구동 방식에 대한 설명 - **1 hour**
    - Function language에 대한 간단한 개요
    - Node.js V8 Engine(Chrome browser engine을 왜 가져다 썼을까?) - **Event loop**의 장단점
    - Typescript 간단히 보기
  - *서버 아키텍처* 비교 - **1 hour**
    - 모노리틱(기존에 많고 많았던...) 아키텍처
    - 서버리스(진짜 서버가 없을까?) 아키텍처
    - **마이크로 서비스 아키텍처**
  - *Docker 맛보기 (Docker hub를 통해 오픈소스 설치해보기)* - **1 hour**
    - Docker 개요(Linux 커널, etc...)
    - Nginx 웹서버 설치(8080:80 포트 매핑)
    - MySQL 설치(기본 설정 및 MySQL client tool 연결)
  - NPM(Node package manager)을 통해 Node.js(v8.11.1 LTS) 설치해보기 - **1hour**
    - NPM vs Yarn
    - what is package.json?
    - 프로젝트 구성에 대한 **Best practice**
- 2주차
  - *Node.js, Express(Web framework), Knexjs(Query builder)을 통해 간단한 CRUD Api 작성해보기* - **4hour**
    - 데이터 요청/응답 기능
    - JWT(Json web token) 인증/인가 기능
    - Email push 기능
    - Postman, Rest client, swagger 등 Api docs를 만들고 테스트
- 3주차
  - *2주차 때 만든 프로젝트를 서비스 단위로 분할하기* - **2 hour**
    - why?
    - 서비스 별 end point 및 라우팅 구성
    - **외부에 오픈될 서비스**와 **내부에서만 접근이 가능한 서비스 단위**로 생각해보기
    - 메인(비즈니스 로직) 서비스와 인증/인가, 이메일(내부) 서비스 통신
  - *Docker file 작성 / 빌드, 컨테이너 운영하기* - **2 hour**
    - Docker 명령어
      - run
      - build
      - option(etc...)
    - Dockerfile 작성
      - RUN
      - FROM
      - CMD
      - etc...
    - 2주차 때 만든 프로젝트를 기반으로 하는 **Docker container** 운영
- 4주차
  - *AWS 사용해보기* - **4 hour**
    - AWS EC2(Amazon linux) 환경에 Docker 설치 및 3주차 때 만든 Dockerfile을 통해 컨테이너 구축하기
    - AWS RDS 환경에서 MySQL 설정
    - AWS Lambda + API Gateway로 EC2 없이(서비리스) 3주차 때 고민한 외부에 오픈할 서비스를 가져와 구축하기
    - AWS ELB을 통한 트래픽 관리
    - Route53에 도메인 등록, ELB를 연결하여 main.\*, api.\* 등 도메인 별 End-point 설정
- 5주차
  - *AWS ECS를 활용한 Container orchestration* - **2 hour**
    - AWS ECR에 n개의 Docker file push
    - EC2 n대를 구성한 후 ECR(docker file)을 기반으로 하여 ECS로 **클러스터링**
      - 작업 정의 구성
      - 컨테이너 별 포트 매핑
      - 컨테이너 Metric(시스템 자원) 배치
  - *AWS ALB(Aplication load balancer)를 활용한 컨테이너 로드밸런싱* - **2 hour**
    - 서비스(컨테이너 그룹) 별 로드밸런싱
    - Route53 도메인/서브도메인 매칭
    - 트래픽 관리 방법 및 **컨테이너 스케일 아웃** 설정
- 6주차
  - *AWS Codepipeline을 활용한 CI/CD* - **4 hour**
    - CI/CD 간단한 개요
    - Github project, webhook 설정
    - 컨테이너 별 자동 배치를 위한 Dockerfile 재작성
    - AWS Codebuild를 통한 자동 빌드(Docker) 설정
    - Codepipeline + Codebuild + ECS를 활용한 **무중단(블루-그린)** 배포
- 7, 8주차 (더 해야 할 내용 키워드만 정리)
  - AWS Beanstalk
  - AWS S3
  - AWS Cloundformation
  - Monitoring (AWS Cloudwatch, ELK stack, Grafana 등)
  - APM (Pinpoint 등)
  - Stress test(nGrinder, jMeter 등) -->