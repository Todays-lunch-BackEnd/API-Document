---
description: 위치 태그와 음식 카테고리에따른 맛집 데이터를 제공하는 API입니다.
---

# Restaurant According to Location Tag and Food Category

## 1. GET method

해당 위치 태그와 음식 카테고리에 따라 선별된 맛집들의 리스트를 반환합니다.

### 1. Request URL

<pre><code><strong>/restaurants/{locationCategory}/{locationTag}&#x26;{foodCategory}
</strong></code></pre>

### 2. Response Body

key : description

* id : 음식점 id
* restaurantImage : 음식점 사진
* restaurantName : 음식점 이름
* restaurantRecmd : 음식점 추천 수
* introduction : 음식점 한줄평
* rating : 음식점 평점
