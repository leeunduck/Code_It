# 형 변환

>처음에 값으로 정해진 자료형을 다른 자료형으로 바꾸는 것

```
// 형 변환 (Type Conversion)
console.log('10' + '5'); ➡️ 105
console.log (10 + 5); ➡️ 15

console.log(Number('10') + Number('5')); ➡️ 15
console.log (String(10) + String(5)); ➡️ 105
```

```
// 숫자 ➡️ 문자
let x = 123;
console.log(x); ➡️ 123
console.log(String(x)); ➡️ 123
console.log(typeof x); ➡️ number
console.log(typeof String(x)); ➡️ string

console.log('');

// 불린 ➡️ 문자
let y = true;
console.log(y); ➡️ true
console.log(String(y)); ➡️ true
console.log(typeof y); ➡️ boolean
console.log(typeof String(y)); ➡️ string
```

```
// 문자 ➡️ 숫자
let x = '123';
console.log(x); ➡️ 123
console.log(Number(x)); ➡️ 123
console.log(typeof x); ➡️ string
console.log(typeof Number(x)); ➡️ number

// 불린 ➡️ 숫자
let y = true;
console.log(y); ➡️ true
console.log(Number(y)); ➡️ 1
console.log(typeof y); ➡️ boolean
console.log(typeof Number(y)); ➡️ number

let y = false;
console.log(y); ➡️ false
console.log(Number(y)); ➡️ 0
console.log(typeof y); ➡️ boolean
console.log(typeof Number(y)); ➡️ number
```

```
// 문자 ➡️ 불린
let x = '문자';
console.log(x); ➡️ 문자
console.log(Boolean(x)); ➡️ true
console.log(typeof x); ➡️ string
console.log(typeof Boolean(x)); ➡️ boolean 

// 숫자 ➡️ 불린
let y = 123;
console.log(y); ➡️ 123
console.log(Boolean(y)); ➡️ true 
console.log(typeof y); ➡️ number
console.log(typeof Boolean(y)); ➡️ boolean

빈 문자 그리고 0 그리고 NAN 값은 false가 나옴
```
