# CI/CD Tools 비교

- 여러 블로그들을 보며 젠킨스란 무엇이고 비슷한 제품들과 어떤 차이가 있는지 알아보자
- 참고
  - https://elfinlas.github.io/2019/08/14/ci-tool/
  - https://owin2828.github.io/devlog/2020/01/09/cicd-1.html

## Travis CI

### 장점

- 다양한 레퍼런스
- 오픈소스 등에서 많이 사용하는 보편적인 CI 도구
- 다양한 언어 지원
- Github과 연동이 편리
- 트래비스에서 자체 호스팅 지원 - 관리 편리함

### 단점

- 젠킨스에 비해 자유도가 낮음 - 젠킨스의 플러그인과 같이 다양하지 않음
- 유료 - 69$ ~
  - https://www.travis-ci.com/pricing/

## Jenkins(젠킨스)

### 장점

- 오픈소스, 무료
- 지원하는 기능이 풍부하고 다양하다
  - 알림의 종류, 다양한 IDE지원, 커스터미즈 등
- 많은 회사에서 주로 사용

### 단점

- 트래비스와는 달리 설치형이라서 젠킨스 자체를 관리하는 것도 하나의 일이 될 수 있다
  - AWS의 EC2같은 독립적인 서버 필요

## TeamCity

- 젠킨스와 같이 설치형
  - 서버 필요
- 깔끔한 UI
- 100개 빌드 구성이하는 무료로 사용 가능

## AWS

## Github Action

## Gitlab CI

## Circle CI
