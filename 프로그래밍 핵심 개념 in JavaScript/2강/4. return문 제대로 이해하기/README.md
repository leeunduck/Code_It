# return문 제대로 이해하기

>어떤 값을 되돌려주는 아웃풋의 역할

```
결과값을 돌려주는 역할
function square(x) {
  return x * x;
}

console.log(square(3));

출력내용 ➡️ 9
```

```
함수의 실행을 중단하는 역할
function square(x) {
  console.log('return 전');
  return x * x;
  console.log('return 후'); // Dead Code
}

console.log('함수 호출 전');
console.log(square(3));
console.log('함수 호출 후');

출력내용 ➡️ return 전
         9
         함수 호출 전
         함수 호출 후
 
return문을 통해 함수 호출 부분에 어떤 값을 되돌려주고 나면 그대로 함수의 실행이 중단이 된다
```
