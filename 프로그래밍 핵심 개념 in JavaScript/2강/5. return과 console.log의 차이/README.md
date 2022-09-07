# return과 console.log의 차이

```
function printSquare(x) {
  console.log(x * x);
}

printSquare(3);

출력내용 ➡️ 9

function getSquare(x) {
  return x * x;
}

getSquare(3);

출력내용 ➡️ 없음

function getSquare(x) {
  console.log(x * x);
}

console.log(getSquare(3));

출력내용 ➡️ undefined (처음부터 아무것도 할당하지 않았다는 의미)
```

>함수를 선언할 때 리턴문을 따로 작성하지 않으면 undefined 값을 리턴 한다

return은 함수를 실행하고 어떤 값을 돌려주는 것

console.log는 콘솔에 어떤 것을 출력해 해주는 함수
