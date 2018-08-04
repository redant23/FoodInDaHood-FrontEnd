# **우리동네 푸드트럭(FoodInDaHood)**

# Introduction

**우리동네 푸드트럭**은 서울지역 푸드트럭 API를 기반으로 자신의 위치 주변에 있는 푸드트럭은 물론 서울 내에 등록된 푸드트럭들의 위치와 운영상황을 확인할 수 있는 푸드트럭 플랫폼입니다.

<img src="https://s3.ap-northeast-2.amazonaws.com/foodindahood/%E1%84%91%E1%85%AE%E1%84%83%E1%85%B3%E1%84%90%E1%85%B3%E1%84%85%E1%85%A5%E1%86%A81.png" width="30%" height="30%"></img>
<img src="https://t1.daumcdn.net/thumb/R1280x0/?fname=http://t1.daumcdn.net/brunch/service/user/1aNR/image/n6m0Uue8FCDVyojFPRO2UQXdotw.png" width="30%" height="30%"></img>
<img src="https://s3.ap-northeast-2.amazonaws.com/foodindahood/%E1%84%91%E1%85%AE%E1%84%83%E1%85%B3%E1%84%90%E1%85%B3%E1%84%85%E1%85%A5%E1%86%A83.png" width="30%" height="30%"></img>


## Requirements


- React, Redux를 사용한 모바일 웹
- NodeJS, Express를 사용하여 서버 구현
- Mlab Database, S3 Storage 사용
- Geolocation, Google map api
- Netlify
- AWS Elastic Beanstalk


## Prerequisites

서울시 푸드트럭 공공 api
npm 설치 및 Xcode와 연결
react, redux 설치

## Installation

### Client
```
git clone https://github.com/yeon0206/FoodInDaHood-FrontEnd
npm install
npm start

```

### Server
```
git clone https://github.com/redant23/FoodInDaHood-BackEnd
npm install
npm run server

```

## Features

- 거리 내 푸드트럭 필터링(500M, 1KM, 2KM, 4KM)
- 거리, 즐겨찾기, 댓글 순으로 정렬기능
- Facebook Social 로그인
- 댓글달기
- 지역, 카테고리, 푸드트럭명 통합검색
- 푸드트럭 즐겨찾기 추가/해제
- 푸드트럭 찾아가기
- 영업상태 실시간 반영


## Client-Side

- Geolocation, google map api
- React, Redux 로 구현
- FB Social Login
- Test Code

## Server-Side

- NodeJS, Express 로 구현
- Mlab을 활용하여 DB 서버구축
- AWS S3를 활용하여 스토리지 서버 구축



## Project Control

- Git을 활용하여 기능추가 및 보완이 될 때마다 커밋하여 관리
- Trello 스케쥴 관리 및 Task 정리
- Netlify(Client), Elastic Beanstalk(Server)를 통한 배포
- Ci 


## Things to do

일반 매장의 경우 시장이 크기 때문에 여러 큰 기업에서 제공하는 서비스가 많지만 푸드트럭의 경우 상대적으로 시장이 적어
서비스가 없었다. 고객의 입장에서는 이동하는 푸드트럭의 영업정보를 알 수 있는 수단이 없고 먹고 싶을 때 찾아가서 먹을 수 있게 
도움을 주는 서비스가 있다면 좋겠다는 생각이 들었다. 트럭운영자의 입장에서도 일반 매장에 비해 홍보수단이 적고 고객과의 소통을 원하는
니즈가 있겠다고 판단했다.(현재 젊은 트럭운영자들 몇 곳만 인스타그램으로 각자 홍보중)
다행히도 서울시에서 제공하는 푸드트럭 공공api가 있어 기본 db 뼈대를 갖추고 서비스 제작을 진행했다.
두 명이서 프론트엔드, 백엔드로 나뉘어 진행했으며, 총괄관리는 한 명이 맡았다.

총괄관리 : [권기연](https://github.com/yeon0206)

프론트엔드 : [권기연](https://github.com/yeon0206)

백엔드 : [김동준](https://github.com/redant23)


Special thanks to [Ken Huh](https://github.com/Ken123777)
