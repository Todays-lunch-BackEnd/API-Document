---
description: 리뷰의 추천수에 대한 API입니다.
---

# Recommendation Review

## 1. POST method

해당 리뷰의 추천 수를 하나 올리거나 내릴 수 있습니다.

### 1. Request URL

```
/restaurants/{restaurantId}/reviews/{reviewId}/recmd
```

### 2. Parameters

path parameter : description

* restaurantId : 음식점의 id
* reviewId : 리뷰의 id
