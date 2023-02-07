---
description: 특정 맛집의 메뉴에 대한 API입니다.
---

# Menus of Restaurant

## 1. GET method

한 맛집의 모든 메뉴 리스트를 반환합니다.

### 1. Request URL

```
/restaurants/{restaurantId}/menus
```

### 2. Parameters

path parameter : description

* restaurantId : 음식점의 id

### 3. Response Body

key : description

* id : 해당 메뉴의 id
* menuImage : 메뉴 사진
* menuName : 메뉴 이름
* menuPrice : 메뉴 가격
* salePrice : 세일된 메뉴 가격
