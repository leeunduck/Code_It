# if문

>어떤 특별한 조건에 따라서 코드를 실행할지 말지 결정할 수 있는 문법

>기본구조
```
// if문 (if statement)
if (조건부분) {
  동작부분
}
➡️ 조건부분이 충족되면 동작 부분을 수행해라 라는 뜻
```

```
EX if문
let temperature = 0;

if (temperature <= 0) {
  console.log('물이 업니다.')
}

출력내용 ➡️ 물이 업니다
```

```
EX if문
let temperature = 1;

if (temperature <= 0) {
  console.log('물이 업니다.')
} else {
  console.log('물이 얼지 않습니다.)
}
  
출력내용 ➡️ 물이 얼지 않습니다.
```
