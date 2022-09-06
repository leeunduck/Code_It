# 불린형 

>JavaScript에서 참과 거짓을 표현하는 자료형을 불린이라고 한다

```
// 불린 (Boolean)
console.log(2 > 1); ➡️ true 2가 1보다 크다
console.log(2 < 1); ➡️ false 2가 1보다 작다
console.log(3 >= 2); ➡️ true 3은 2보다 크거나 같다
console.log(3 <= 3); ➡️ true 3은 2보다 작거나 같다
console.log(3 === 3); ➡️ true 값이 서로 일치한다
console.log(3 !== 3); ➡️ false 값이 서로 일치하지 않는다
```

```
// 불린 응용
console.log("unducklee" === "unducklee"); ➡️ true
console.log("unducklee" !== "unduklee"); ➡️ true
```

```
// 불린 연산
<AND 연산>
console.log(true && true); ➡️ true
console.log(true && false); ➡️ false
console.log(false && true); ➡️ false
console.log(false && false); ➡️ false

<OR 연산>
console.log(true || true); ➡️ true
console.log(true || false); ➡️ true
console.log(false || true); ➡️ true
console.log(false || false); ➡️ false

<NOT 연산>
console.log(!true); ➡️ false
console.log(!false); ➡️ true
```
