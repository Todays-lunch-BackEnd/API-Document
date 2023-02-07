---
description: 심사 대상의 맛집에 대한 API입니다.
---

# Judgement

## 1. GET method

심사 중인 맛집 리스트를 반환합니다.

### 1. Request URL

```
/judgements
```

### 2. Response Body

key : description

* id : 심사 중인 음식점의 id
* restaurantImage : 음식점 사진
* restaurantName : 음식점 이름
* writer : 등록자의 nickname
* address : 음식점 주소
* foodCategory : 음식 카테고리
* locationCategory : 위치 카테고리
* locationTag : 위치 태그
* agreement : 추천 수

### 3. Response Body Example



## 2. POST method

심사할 맛집을 추가합니다.

### 1. Request URL

```
/judgements
```

### 2. Request Body

key of request body : description

* restaurantImage : 음식점 사진
* restaurantName : 음식점 이름
* locationTag : 위치 태그
* locationCategory : 위치 카테고리
* foodCategory : 음식 카테고리
* address : 음식점 주소
* userId : 글쓴이의 id

### 3. Request Body Example

### 4. Response Body

### 5. Response Body Example



## 3. PATCH method

심사 중인 맛집의 추천 수를 올립니다.

### 1. Request URL

```
/judgements
```
