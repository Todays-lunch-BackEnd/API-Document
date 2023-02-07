---
description: 유저 정보를 업데이트/반환하는 API입니다.
---

# MyPage

## 1. GET method

해당 유저 정보를 반환합니다.

### 1. Request URL

```
/mypage/{userId}
```

### 2. Parameters

path parameter : description

* userId : 유저의 id

### 3. Response Body

key : description

* id : 유저의 email id
* nickname : 유저의 닉네임
* locationCategory : 유저의 위치
* foodCategory : 유저의 음식 카테고리 취향
* icon : 프로필 아이콘

## 2. PATCH method

해당 유저 정보를 수정합니다.&#x20;

### 1. Request URL

```
/mypage/{userId}
```
