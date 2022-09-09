# 객체에서 데이터 접근하기

>객체도 결국은 값이기 때문에 객체를 다루기 위해서는 먼저 변수에 할당해 주면서 이름을 만들어 주어야 한다

```
// 객체 (object)

let unducklee = {
  name: 'unducklee',
  bornYear: 1998,
  isVeryNice: true,
  worstCourse: null,
  bestCourse: {
    title: '자바스크립트 프로그래밍 기초',
    language: 'JavaScript'
  }
};
```

>객체의 프로퍼티에 접근하는 방법

1. 점표기법

```
console.log(unducklee.bornYear);

출력내용 ➡️ 1998

주의사항 프로퍼티 네임이 따옴표로 감싸져 있다면 접근을 할 수 없게됨
```

2. 대괄호 표기법

```
프로퍼티 네임이 'born Year'일시

console.log(unducklee['born Year'])

출력내용 ➡️ 1998
```

>객체 안의 객체에 접근하는 방법

```
console.log(unducklee.bestCourse.title);

출력내용 ➡️ 자바스크리브 프로그래밍 기초

점표기법으로 접근할 수 없다면 대괄호 표기법으로 접근
```

>존재하지 않은 프로퍼티에 접근한다면

출력내용 ➡️ undefined 
