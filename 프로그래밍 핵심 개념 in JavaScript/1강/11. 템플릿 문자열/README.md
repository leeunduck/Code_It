# 템플릿 문자열

```
템플릿 문자열 (Template strings)
template: 일정한 틀, 형식

let year = 2018;
let month = 3;
let day = 11;

console.log('생년월일은 ' + year + '년 ' + month '월 ' + day '일 입니다.')
➡️ 생년월일은 2018년 3월 11일 입니다.

console.log(`생년월일은 ${year}년 ${month}월 ${day}일 입니다.`)
➡️ 생년월일은 2018년 3월 11일 입니다.
```

```
let myNumber = 3;

function get_twice(x) {
  return x * 2;
};

console. log(`${myNumber}의 두 배는 ${get_twice(myNumber)}입니다.`);
➡️ 3의 두 배는 6입니다.
```
