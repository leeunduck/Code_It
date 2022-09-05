# return문

## JavaScript에서의 output (return)

>함수 내부에서 정해진 명령들을 실행하고 난 뒤에 다시 돌려준다, 반환한다는 의미

```
function get_two() {
  return 2;
};

console.log(get_two());

➡️ console.log(2);와 동일한 코드가 된다
```

```
function get_twice(number) {
  return number * 2;
};

console.log(get_twice(5));

➡️ console.log(10);과 같은 코드가 된다
```

```
function get_twice(number) {
  return number * 2;
};

let x = get_twice(5);
let y = get_twice(2);

console.log(x * y);

출력내용 ➡️ 40
```
