# for...of 반복문

>배열의 각 요소를 대상으로 반복적인 작업을 수행할 때는 for..of문을 활용하는 것이 좋다

```
// for..of 반복문
for..of 기본구조

for (변수 of 배열) {
  동작부분;
};
```

```
let influencer = ['hyun', 'seok', 'lee'
'kim', 'soo'];

for (let element of influencer) {
  console.log(element);
};

➡️ 
hyun
seok
lee
kim
soo
```
