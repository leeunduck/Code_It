# 파라미터 (매개변수)

```
console.log()
```
라는 함수를 살펴 보면

소괄호 안에 어떤 값들을 입력하고 있다

**함수를 호출할 때 소괄호 안에 입력하는 값을 파라미터 (매개변수)라고 한다**

```
//함수 선언
                  ⬇️ 파라미터
function greeting(sentence) {
  console.log("Hello");
  console.log("안녕하세요");
  console.log(sentence);
};

// 함수 호출
greeting("Hello");

출력내용
Hello
안녕하세요
Hello

➡️ 함수를 호출할 때 이 Hello라는 문자열이 함수 선언 부분에서 sentence라는 파라미터로 전달되고 
함수 내부에서는 이 sentence가 Hello라는 값을 가진 변수처럼 활용이 돼서 
결과적으로 마지막에 이 sentence의 값인 Hello도 같이 출력되는 걸 볼 수 있다
```

```
function welcome(name) {
  console.log("안녕하세요" + name + '님');
};

welcome('이현석');

출력내용
안녕하세요 이현석님
```
