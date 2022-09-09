# Date 객체

## 내장 객체 (Standard built - in objects)

>JavaScript가 미리 가지고 있는 객체

```
let my_date = new Date();

➡️ 객체를 생성한 순간의 시간이 출력됨
```

```
let my_date = new Date('2022-08-09T23:08:10');
console.log(my_date)
➡️ Fri September 09 2022 23:08:10 GMT+0900 (대한민국 표준시)

주의사항: 월은 0부터 시작하기 때문에 8월을 적으면 9월로 표기됨
```

```
let my_date = new Date(YYYY, MM, DD, hh, mm, ss, ms);
```
