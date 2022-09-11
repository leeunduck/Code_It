# 기본형과 참조형

## 자료형

>Number
>
>String
>
>Boolean
>
>Null
>
>Undefined
>
>Object

## 기본형 (Primitive Type)
>Number
>
>String
>
>Boolean
>
>Null
>
>Undefined

```
let x = 3;
let y = x;

console.log(x);
console.log(y);
y = 5;

console.log(x);
console.log(y);

➡️ 3
➡️ 3
➡️ 3
➡️ 5
```

## 참조형 (Reference Type)

>Object
>
>배열

```
let x = {name : 'unducklee'};
let y = x;

console.log(x);
console.log(y);
y.birth = 1998;
console.log(x);
console.log(y);

➡️ {name : 'unducklee'}
➡️ {name : 'unducklee'}
➡️ {name : 'unducklee', birth : 1998}
➡️ {name : 'unducklee', birth : 1998}
```

>변수에 객체 값을 할당한 경우

>>객체 값이 어딘가에서 만들어지고 변수에는 그 객체 값으로 가는 주소가 저장된다 (변수 상자와 객체 값 사이의 길이 열리는 것)
