# 상수

>절대 변하지 않고 항상 일정한 값

```
// 상수 (constant)
const MY_NUMBER = 3.14; // 원주율 ➡️ const라는 함수를 사용하면 상수로 고정됨
let radius = 0; // 반지름

// 원의 넓이를 계산하는 함수
function calculateArea() {
  return pi * radius * radius;
}

// 반지름에 따른 원의 넓이를 출력하는 함수
function printArea() {
  return `반지름이 ${radius}일 때, 원의 넓이는 ${calculateArea()}`;
}

radius = 4;
console.log(printArea());

radius = 7;
console.log(printArea());

radius = 8;
console.log(printArea());

출력내용 ➡️ 반지름이 4일 때, 원의 넓이는 1650.24
         반지름이 7일 때, 원의 넓이는 19153.86
         반지름이 8일 때, 원의 넓이는 22200.96
```
