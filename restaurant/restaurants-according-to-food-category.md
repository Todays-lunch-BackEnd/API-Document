---
description: 음식 카테고리에 따른 맛집 데이터를 제공하는 API입니다.
---

# Restaurants According to Food Category

## 1. GET method

해당 음식 카테고리에 따라 선별된 맛집들의 리스트를 반환합니다.

### 1. Request URL

```
/restaurants/food-category
```

### 2. Parameters

request parameter : description

* categoryName : 음식 카테고리 이름

### 3. Request Example

```
/restaurants/food-category?categoryName=korean
```

### 4. Response Body

key : description

* id : 음식점 id
* restaurantImage : 음식점 사진
* restaurantName : 음식점 이름
* introduction : 음식점 한줄평
* rating : 음식점 평점
* locationCategory: 위치 카테고리
* locationTag: 위치 태그
* foodCategory: 음식 카테고리
* latitude: 위도
* longitude: 경도
* rating: 리뷰들의 평점 평균
* reviewCount: 리뷰 개수

### 5. Response Body Example
