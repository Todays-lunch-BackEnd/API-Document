---
description: 유저가 찜한 맛집에 대한 API입니다.
---

# MyStore

## 1. GET method

찜한 맛집들의 리스트를 반환합니다.

### 1. Request URL

```
/mypage/{userId}/mystore
```

### 2. Parameters

path parameter : description

* userId : 유저의 id

### 3. Response Body

key : description

* restaurantName : 찜한 메뉴의 이름
* restaurantName : 메뉴의 레스토랑 이름
