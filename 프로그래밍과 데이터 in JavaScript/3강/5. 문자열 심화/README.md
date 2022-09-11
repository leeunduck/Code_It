# 문자열 심화

```
let my_string = 'Hi unducklee';

// length 프로퍼티: 문자열의 길이를 알려준다
console.log(my_string.length);

➡️ 11
```

```
let my_string = 'Hi unducklee';

// 요소 접근
console.log(my_string.charAt(3));
console.log(my_string[3]);

➡️ u
```

```
let my_string = 'Hi unducklee';

// 요소 탐색
console.log(my_string.indexOf('e')); // 앞부터
console.log(my_string.lastIndexOf('e')); // 뒤부터

➡️ 10
➡️ 0
```

```
let my_string = 'Hi unducklee';

// 대문자 소문자 변화 메소드
console.log(my_string.toUpperCase()); // 대문자
console.log(my_string.toLowerCase()); // 소문자

➡️ HI UNDUCKLEE
➡️ hi unducklee
```

```
let my_string = '   Hi unducklee  ';

// trim 메소드: 양 끝 공백 제거
console.log(my_string.trim());

➡️ Hi unducklee
```

```
let my_string = '   Hi unducklee  ';

// 부분 문자열 접근 slice(stard, end)
console.log(my_string.slice(0, 2));
console.log(my_string.slice(3));
console.log(my_string.slice());

➡️ Hi
➡️ unducklee
➡️ Hi unducklee
```
