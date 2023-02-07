---
description: 맛집의 상세 페이지에 대한 API 입니다.
---

# Detail for Restaurant

## 1. GET method

하나의 맛집에 대한 정보를 반환합니다.

### 1. Request URL

```
/restaurants/{restaurantId}
```

### 2. Parameters

path parameter : description

* restaurantId : 음식점의 id

### 3. Response Body

key : description

* id : 음식점 id
* restaurantImage : 음식점 사진
* restaurantName : 음식점 이름
* restaurantRecmd : 음식점 추천 수
* restaurantDecmd : 음식점 비추천 수
* introduction : 음식점 한줄평
* rating : 음식점 평점
* writer : 맛집을 등록한 유저의 nickname
* address : 맛집의 주소(도로명 등)

### 4. Response Body Example

## 2. POST method

### 1. Request URL

```
/restaurants/{restaurantId}
```
