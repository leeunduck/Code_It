# 변수의 scope

변수가 선언되면 어디까지 유효한지 즉 변수의 유효 범위는?



```
// Scope: 범위, 영역
let x = 3; // 글로벌 변수, 전역 변수 (Global Variable)
console.log(x);

출력내용 ➡️ 3

function myFunction() { // 블록문 (Block Statement)
  let x = 3;  // 로컬 변수, 지역 변수 (Local Variable) ➡️ 블록문 내에서만 사용 가능한 변수
  console.log(x);
}

myFunction();

출력내용 ➡️ 3

function myFunction() {
  let x = 3;
  console.log(x);
}

myFunction();
console.log(x);

출력내용 ➡️ 3
         Error
```
