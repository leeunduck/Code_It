# break와 continue
>break
```
let i = 1;

while (i <= 10 {
  console.log(i);
  if (i === 7) {
    break;
  }
  i++
}

숫자 7에 다다르면 while문을 빠져나옴
```

```
for (let i = 1; i <= 10; i++) {
  console.log(i);
  if (i === 7) {
    break;
  }
}
```

>continue (동작부분을 한번 건너뛰는 것)

```
for (let i = 1; i <= 10; i++) {
  if (i % 2 === 0) {
    continue;
  }
  console.log(i);
}

출력내용 ➡️ 1, 3, 5, 7, 9
```

```
while (i <= 10 {
  if (i % 2 === 0) {
    continue;
  }
  console.log(i);
  i++
}
```
