# 옵셔널 파라미터

```
function sayHello(name) {
  console.log(`안녕하세요 ${name}님!`);
}

sayHello('이현석')
sayHello('김수정')
sayHello('unducklee')

출력내용 ➡️ 안녕하세요 이현석님!
         안녕하세요 김수정님!
         안녕하세요 unducklee님!
         
undefined값을 받는 과정
let x;
console.log(x)
console.log(sayHello('이현석최고'));

➡️ 변수를 선언하고 아무런 값을 할당하지 않았을 때
➡️ 함수를 호출 했는데 리턴문이 작성되어 있지 않는 경우
➡️ 함수를 호출할 때 파라미터에 아무런 값도 전달하지 않았을 경우
```

## 옵셔널 파라미터
선택적으로 파라미터를 받는다

```
// 옵셔널 파라미터
function introduce(name, age, nationlity = '한국')
  console.log(`제 이름은 ${name}입니다.`);
  console.log(`나이는 ${age}살 이고,`);
  console.log(`국적은 ${nationlity}입니다.`);
}

introduce('이현석', 25, '한국'); // 값을 모두 전달한 경우
console.log('');
introduce('김수정', 25); // 파라미터 값을 생략한 경우

출력내용
제 이름은 이현석 입니다.
나이는 25살 이고,
국적은 한국입니다.

제이름은 김수정 입니다.
나이는 25살 이고,
국적은 한국입니다.
```

>옵셔널 파라미터는 선언을 할 때 반드시 생성한 다음 가장 뒤쪽으로 선언해 줘야 
