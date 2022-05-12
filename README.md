## 🥐 BBangMap Server

> 당신의 후회없는 빵 선택을 도와줄 브레드 맵, 지도기반 빵집 추천 앱 서비스 ✨

![표지](https://user-images.githubusercontent.com/76844556/168022567-8200bb68-92b7-43f3-8143-2ee08b0591be.png)


<div align="center">
<img src="https://img.shields.io/badge/Node.js-v14-43853D?logo=node.js"/> <img src="https://img.shields.io/badge/Javascript-es6-F7DF1E?logo=javascript"/></br>
<img src="https://img.shields.io/badge/Express-v4.17.1-404D59?logo=express"/>  <img src="https://img.shields.io/badge/Sequelize-v6.11.0-FFCA28?logo=sequelize"/> <img src="https://img.shields.io/badge/MySQL-v8.0.23-316192?logo=mysql"/> 
</div>

<br/><br/>

## 🍞 Core Service

<p float="left">
<image width=33% src="https://user-images.githubusercontent.com/76844556/168022804-1b3722c8-d7ca-48f8-81c8-ff178610d4f5.png">
<image width=33% src="https://user-images.githubusercontent.com/76844556/168022793-794c37c6-6e03-4418-a4fa-53885c6a9ce9.png">
<image width=33% src="https://user-images.githubusercontent.com/76844556/168022777-a56d8304-1e3a-4cf8-967d-7ef61f6a2ec3.png">
</p>
<p float="left">
<image width=33% src="https://user-images.githubusercontent.com/76844556/168022696-e6fc9d6b-74f0-4a19-8c60-ac5a6ffe8a8e.png">
<image width=33% src="https://user-images.githubusercontent.com/76844556/168022672-4f089eb8-0ab7-42f1-81e2-3787843466e2.png">
</p>

    
<hr>
<br/>

## 🥖 Contributors
  <image width=50% src="https://user-images.githubusercontent.com/76844556/136992169-2336db29-66e3-4908-90d8-902d6908ff6a.png">

|                                                         `Lead`  이현종                                                         |                                                             이솔                                                              |                                                            강한희                                                             |
| :---------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: |
|                                           [@hyunjong-96](https://github.com/hyunjong-96)                                            |                                         [@soleu](https://github.com/soleu)                                          |                                            [@kanghanhee](https://github.com/kanghanhee)                                             |

<hr>

<br/>

## 🥨 ERD

![bbang_map_erd](https://user-images.githubusercontent.com/76844556/168024339-ecc7f962-78f0-410b-ab13-97252f9bc00b.png)
  

<hr>
</br>

## 🍰 Role

|  Route   |               Func               |  Role  |
| :------: | :------------------------------: | :----: |
|   AUTH   |           소셜 로그인            | 이현종 |
|          |           토큰 재발급            | 이현종 |
|          |             로그아웃             | 이현종 |
|   USER   |         닉네임 중복 검사         |  이솔  |
|          |           랜덤 닉네임            |  이솔  |
|          |           프로필 수정            |  이솔  |
|          |            회원 탈퇴             |  이솔  |
|  BAKERY  |            빵집 검색             | 이현종 |
|          |        빵집 지역으로 검색        |  이솔  |
|          |          빵집 지도 조회          | 이현종 |
|          |          빵집 상세보기           | 이현종 |
|          |       빵집 이미지 전체보기       | 이현종 |
|          |      빵집 보관 / 가고싶어요      | 이현종 |
|  REVIEW  |       후기 빵집별 전체보기       | 강한희 |
|          |          후기 전체보기           | 강한희 |
|          |          후기 상세보기           | 강한희 |
|          |     후기 빵집, 이름으로 검색     | 강한희 |
|          |          후기 상세보기           | 강한희 |
|          |         후기 추천 / 취소         | 강한희 |
|          |            후기 보관             | 강한희 |
|          |          후기 수정하기           | 강한희 |
|          |          후기 작성하기           | 강한희 |
|  MYPAGE  |         마이페이지 조회          |  이솔  |
|          |     내 보관 빵집 리스트 조회     | 이현종 |
|          | 내 후기 보관함 빵집 폴더별 조회  | 강한희 |
|          |    내 후기 보관함 빵집별 조회    | 강한희 |
|          |       보관한 빵집 삭제하기       | 이현종 |
|          |       보관한 후기 삭제하기       | 강한희 |
| MISSION  |       이달의 미션 조회하기       |  이솔  |
|          |       완료한 미션 조회하기       |  이솔  |
|          |        나의 등급 조회하기        |  이솔  |
|          |       미션 빵집 방문 체크        |  이솔  |
| CURATION |        큐레이션 추가하기         | 이현종 |
|          |        큐레이션 상세보기         | 이현종 |
|          | 큐레이션 빵집 위치 정보 조회하기 | 이현종 |
|          |      큐레이션 좋아요 / 취소      | 이현종 |

</br>

## 🥪 Convention

- [Commit Convention](https://github.com/bbangmap/BBangMap-Server-Docs/wiki/Commit-Convention)
- [Coding Convention](https://github.com/bbangmap/BBangMap-Server-Docs/wiki/Coding-Convention)
- [Git Convention](https://github.com/bbangmap/BBangMap-Server-Docs/wiki/Git-Convention)

<hr>
</br>

## 🍪 Project Foldering

```
🗂 BBangMap-Server
    🗂 api
        🗂 routes
            🗂 auth
            🗂 bakery
            🗂 curation
            🗂 mission
            🗂 review
            🗂 user
            - index.js
        - index.js
    🗂 src
        🗂 auth
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 bakery
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 curation
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 mission
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 review
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        🗂 user
            🗂 controller
            🗂 service
            🗂 model
            🗂 dto
        - index.js
    🗂 models
        🗂 modelUtil
        - index.js
    🗂 modules
        🗂 multer
        🗂 uuidUtil
        - definition.js
        - jwt.js
        - responseMessage.js
        - statusCode.js
        - util.js
    🗂 config
        - config.json
        - s3.js
        - secretJwtKey.js
    🗂 other
        - slackAPI.js
        - slackSender.js
        - jwt.js
        - relationStatus.js
        - reportReason.js
        - responseMessage.js
        - slackMessage.js
        - statusCode.js
    🗂 middlewares
        - authUtil.js
```

<hr>

</br>

## 🧁 Dependencies Module

```json
{
  "name": "bbangmap-server",
  "version": "0.0.0",
  "private": true,
  "scripts": {
    "start": "node ./bin/www"
  },
  "dependencies": {
    "@types/sequelize": "^4.28.10",
    "aws-sdk": "^2.1028.0",
    "axios": "^0.26.0",
    "cookie-parser": "~1.4.4",
    "debug": "~2.6.9",
    "dotenv": "^16.0.0",
    "express": "^4.17.1",
    "http-errors": "~1.6.3",
    "jade": "^0.29.0",
    "jsonwebtoken": "^8.5.1",
    "morgan": "~1.9.1",
    "multer": "^1.4.3",
    "multer-s3": "^2.10.0",
    "mysql2": "^2.3.2",
    "nodemon": "^2.0.7",
    "pug": "^3.0.2",
    "sequelize": "^6.11.0",
    "sequelize-cli": "^5.0.0"
  }
}

```
