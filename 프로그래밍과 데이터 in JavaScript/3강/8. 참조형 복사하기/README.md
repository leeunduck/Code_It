# 참조형 복사하기

```
// 참조형 복사하기 (Reference Type Copy)
let numbers1 = [1, 2, 3];
let number2 = numbers1;

numbers2.push(4);

console.log(numbers1);
console.log(numbers2);

➡️ [1, 2, 3, 4]
➡️ [1, 3, 4, 4]


let numbers1 = [1, 2, 3];
let number2 = numbers1.slice();

numbers2.push(4);

console.log(numbers1);
console.log(numbers2);

➡️ [1, 2, 3]
➡️ [1, 3, 4, 4]
```

```
let course1 = {
  title: '파이썬 프로그래밍 기초'
  language: 'python'
};

let course2 = course1;

course2.title = '알고리즘의 정석';

console.log(course1);
console.log(course2);

➡️ {title: 알고리즘의 정석, language: python}
➡ {title: 알고리즘의 정석, language: python}


let course1 = {
  title: '파이썬 프로그래밍 기초'
  language: 'python'
};

let course2 = Object.assign({}, course1);

course2.title = '알고리즘의 정석';

console.log(course1);
console.log(course2);

➡️ {title: 파이썬 프로그래밍 기초, language: python}
➡ {title: 알고리즘의 정석, language: python}
```

```
let course1 = {
  title: '파이썬 프로그래밍 기초'
  language: 'python'
};

let course2 = {};

for (let key in course1) {
  course2[key] = course1[key];
};

course2.title = '자료구조';

console.log(course1);
console.log(course2);

➡️ {title: 파이썬 프로그래밍 기초, language: python}
➡ {title: 자료구조, language: python}
```
