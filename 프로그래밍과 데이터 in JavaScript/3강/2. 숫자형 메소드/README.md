# 숫자형 메소드

```
let my_number = 0.3591;

// toFixed (0 ~ 100) : 파라미터로 숫자 값을 전달해 주면 그만큼 소수점 아래의 자릿수를 고정해 주는 메소드
console.log(my_number.toFixed(3));

➡️ 0.359 (문자열)
```
```
let my_number = 255;

//toString (2 ~ 36): 파라미터로 전달하는 숫자의 진법으로 숫자를 변화해 주는 메소드이다
console.log(my_number.toString(2));
console.log(my_number.toString(8));
console.log(my_number.toString(16));

➡️ 11111111
377
ff
```
