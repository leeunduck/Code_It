문자열도 생각해보면 '문자' + '열'이기 때문에 배열과 비슷한 부분들이 많습니다.

## 비슷한 점
실제로 지난 시간에 배열과 문자열 모두 length프로퍼티를 가지고 있고, 대괄호 표기법으로 각 요소에 접근할 수 있다거나..

꽤 많은 메소드들이 배열과 문자열 모두 동일하게 사용되는 것도 확인할 수 있었는데요. 

심지어 지난 시간에 다루진 못했지만 배열을 다룰 때 유용한 for..of문을 문자열에 활용할 수도 있습니다.

```
let myString = 'Codeit';

for (let str of myString) {
  console.log(str);
}

➡️ C
o
d
e
i
t
```

## 다른 점
하지만 비슷하다고 해서 완전히 같다고는 할 수 없습니다.

```
let myString = 'Codeit';
let myArray = ['C', 'o', 'd', 'e', 'i', 't'];

console.log(typeof myString);
console.log(typeof myArray);
```

일단 typeof 연산자를 사용해서 두 값의 자료형을 비교해보면,

```
string
object
```

string과 object, 확실히 서로 다른 자료형인 걸 확인할 수 있고,

```
let myString = 'Codeit';
let myArray = ['C', 'o', 'd', 'e', 'i', 't'];

console.log(myString === myArray);
console.log(myString == myArray);
```

두 값을 서로 비교해 보아도

```
false
false
```

일치 비교뿐만 아니라, 느슨하게 비교하는 동등비교에서도 false가 출력되는걸 확인할 수 있습니다.

## mutable vs. immutable
가장 중요한 차이는 **배열은 'mutable(바뀔 수 있는)'** **자료형**인 반면 **문자열**은 **'immutable(바뀔 수 없는)' 자료형**이라는 것입니다.

배열은 요소에 접근해서 할당연산자를 통해 요소를 수정할 수 있었죠?

문자열은 한 번 할당된 값을 수정할 수 없습니다. 다르게 표현해서, 변수에 할당된 문자열을 바꾸고 싶다면, 일부를 바꾸는 게 아니라 새로운 문자열을 지정해주어야 한다는 것이죠.

```
// 배열은 mutable
let myArray = ['C', 'o', 'd', 'e', 'i', 't'];
myArray[0] = 'B';
console.log(myArray);

// 문자열은 immutable
let myString = 'Codeit';
myString[0] = 'B';
console.log(myString);

➡️ (6) ["B", "o", "d", "e", "i", "t"]
Codeit
```

다시 한번 되돌아보면, 문자열이 가진 메소드들은 모두 return 값들을 활용하고, 

본래의 문자열 값을 수정하지 않습니다. 
같은 의미에서 문자열에 splice 같은 메소드들은 사용할 수 없겠죠?

문자열과 배열은 서로 비슷하지만 엄연히 다른 차이가 있다는 점 꼭 기억해 주세요!
