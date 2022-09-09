# for...in 반복문

>객체 안에 있는 프로퍼티를 가지고 반복적인 동작을 수행할 때 사용

```
기본구조

for(변수 in 객체) {
  동작부분
}
```

```
let unducklee = {
  name: 'unducklee',
  bornYear: 1998,
  isVeryNice: true,
  worstCourse: null,
  bestCourse: '자바스크립트 프로그래밍 기초'
};

for(let k in unducklee) {
  console.log(k);
  console.log(unducklee[k]);
}

➡️ name
  unducklee
  bornYear
  1998
  isVeryNice
  true
  worstCourse
  null
  bestCourse
  자바스크립트 프로그래밍 기초
```
