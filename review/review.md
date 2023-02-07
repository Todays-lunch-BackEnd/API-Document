---
description: 해당 음식점의 리뷰들에 대한 API입니다.
---

# Review

## 1. GET method

해당 음식점의 모든 리뷰들의 리스트를 반환합니다.

### 1. Request URL

```
/restaurants/{restaurantId}/comments
```

### 2. Parameters

path parameter : description

* restaurantId : 음식점의 id

### 3. Response Body

key : description

* id : 리뷰의 id
* nickname : 글쓴이의 닉네임
* icon : 글쓴이의 아이콘 사진
* rating : 평점
* reviewRecmd : 추천 수
* reviewDecomd : 비추천 수
* reviewContent : 한 줄 리뷰 내용

## 2. POST method

리뷰를 작성합니다.

### 1. Request URL

```
/restaurants/{restaurantId}/reviews
```

### 2. Parameters

path parameter : description

* restaurantId : 음식점의 id

key of request body : description

* id : 리뷰의 id
* userId : 글쓴이의 id
* rating : 평점
* reviewContent : 한 줄 리뷰 내용

## 3. PATCH method

리뷰를 수정합니다.

### 1. Request URL

```
/restaurants/{restaurantId}/reviews/{reviewId}
```

### 2. Parameters

path parameter : description

* restaurantId : 음식점의 id
* reviewId : 리뷰의 id

## 4. DELETE method

리뷰를 삭제합니다.

### 1. Request URL

```
/restaurants/{restaurantId}/reviews/{reviewId}
```

### 2. Parameters

path parameter : description

* restaurantId : 음식점의 id
* reviewId : 리뷰의 id
