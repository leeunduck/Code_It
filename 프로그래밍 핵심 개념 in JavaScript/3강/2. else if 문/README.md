# else if 문

>두가지 이상의 옵션이 필요하다면 else if문 쓰기

```
EX if문
let temperature = 1;

if (temperature <= 0) {
  console.log('물이 업니다.');
} else {
  if (teperature < 100) {
    console.log('물이 얼지도 끓지도 않습니다');
  } else {
    console.log('물이 끓습니다.')
} 

코드내용: 온도가 0도 이하이면 '물이 업니다' 출력
        온도가 0도 이하가 아니고 100도 이상이 아니면 '물이 얼지도 끓지도 않습니다' 출력
        온도가 100도 이상이면 '물이 끓습니다' 출력
```

```
EX else if문
let temperature = 105;

if (temperature <= 0) {
  console.log('물이 업니다.');
} else if (temperature < 100) {
  console.log('물이 얼지도 끓지도 않습니다.');
} else {
  console.log('물이 끓습니다')
}

출력내용 ➡️ 물이 끓습니다.
```
