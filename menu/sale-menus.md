---
description: 세일하는 메뉴에 대한 API입니다.
---

# Sale Menus

## 1. GET method

현재 세일 중인 메뉴들의 리스트를 반환합니다.

### 1. Request URL

```
/sale-menus
```

### 2. Response Body

key : description

* id : 해당 메뉴의 id
* menuImage : 메뉴 사진
* menuName : 메뉴 이름
* menuPrice : 메뉴 가격
* salePrice : 세일된 메뉴 가격
* writer : 세일 메뉴 등록자의 nickname

### 3. Response Body Example

## 2. POST method

세일하는 메뉴를 유저가 추가할 수 있습니다.

### 1. Request URL

```
/sale-menu/menuId
```

### 2. Parameters

path parameter : description

* restaurantId : 음식점의 id

key of request body : description

* salePrice : 메뉴의 세일된 가격
* startDate : 세일 시작 날짜
* endDate : 세일 종료 날짜
