# 객체 다루기

>객체 수정하기

```
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

console.log(unducklee.name);
unducklee.name = hynuseoklee;
console.log(unducklee.name);

출력내용 ➡️ unducklee
        hyunseoklee
```

>객체 추가하기

```
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

console.log(unducklee.ceo);
unducklee.ceo = hynuseoklee;
console.log(unducklee.ceo);

➡️ undefined
  hyunseoklee
```

>객체 삭제하기

```
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

console.log(unducklee.ceo);
delete unducklee.ceo;
console.log(unducklee.ceo);

➡️ hyunseoklee
  undefined
```

>객체의 프로퍼티 존재 여부

```
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

console.log(unducklee.name !== undefined);

console.log('name' in unducklee)

➡️ true
  true

프로퍼티를 확인할 때 좀 더 안전하기 위함
```
