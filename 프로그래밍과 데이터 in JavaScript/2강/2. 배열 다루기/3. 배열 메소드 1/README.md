# 배열 메소드 1

```
// 삭제
let members = ['쿤갈레', 'Zerrard66', '우리생각해써',
'흙토끼', 'End Miracle'];

members.splice(삭제할 인덱스번호, 삭제할 개수, 삭제한 요소 자리에 추가할 값);
members.splice(0, 1, '이현석', '김수정');
console.log(members);

➡️ 이현석, 김수정, Zerrard66, 우리생각해써, 흙토끼, End Miracle
```
