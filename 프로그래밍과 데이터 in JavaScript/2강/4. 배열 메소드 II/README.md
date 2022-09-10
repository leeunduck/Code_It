# 배열 메소드 2

```
let members = ['쿤갈레', 'Zerrard66', '우리생각해써',
'흙토끼', 'End Miracle'];

// 배열의 첫 요소를 삭제: shift()
members.shift();
console.log(members);

➡️ Zerrard66, 우리생각해써, 흙토끼, End Miracle

// 배열의 마지막 요소를 삭제: pop()
members.pop();
console.log(members);

➡️ Zerrard66, 우리생각해써, 흙토끼

// 배열의 첫 요소로 값 추가: unshift(Value)
members.unshift('이현석');
console.log(members);

➡️ 이현석, Zerrard66, 우리생각해써, 흙토끼

// 배열의 마지막 요소로 값 추가: push(Value)
members.push('김수정');
console.log(members);

➡️ 이현석, Zerrard66, 우리생각해써, 흙토끼, 김수정
```
