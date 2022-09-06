# typeof 연산자

>typeof라는 키워드 다음에 값을 입력하면 이 값을 평가해서 해당하는 자료형을 문자열로 되돌려 준다

```
// typeof 연산자
console.log(typeof 101); ➡️ number
console.log(typeof "unducklee"); ➡️ string
console.log(typeof true); ➡️ boolean
```

```
console.log(typeof 1); ➡️ number
console.log(typeof 1.0); ➡️ number
console.log(typeof "1"); ➡️  string
console.log(typeof '1'); ➡️  string
console.log(typeof `1`); ➡️  string
```

```
let name = 'unducklee';
function sayHello() {
  console.log('Hello');
};

console.log(typeof name);
console.log(typeof sayHello);

➡️ string
➡️ function
```

```
console.log(typeof 'Hello' + 'unducklee'); ➡️ stringunducklee
console.log(typeof 8 - 3); ➡️ NaN (숫자가 아닌 값)

typeof 연산자는 기본적으로 사칙연산자들보다 우선순위가 높다 (괄호를 사용해 연산자의 우선순위를 높이면 된다)
```
