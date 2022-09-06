# 형 변환 2

```
console.log('4' - true); ➡️ 자동으로 형변환 되어 3이 나옴
```

```
산술 연산 (+, -, *, /, %, **)
console.log(4 + '2'); ➡️ 42 (문자열 연산)
console.log(4 + 2); ➡️ 6
console.log(4 - true); ➡️ 3
console.log(4 - false); ➡️ 0
console.log(4 / '2'); ➡️ 2
console.log('4' ** true); ➡️ 4
console.log(4 % 'two'); ➡️ NaN
```

```
관계 비교 연산 (<, <=, >, >=)
console.log(2 < '3'); ➡️ true
console.log(2 > true); ➡️ true
console.log('2' <= false); ➡️ false
console.log('two' >= 1); ➡️ false
```

```
같음 비교 연산 (===, !==, ==, !=)
console.log(1 === '1'); ➡️ false
console.log(1 === true); ➡️ false
console.log(1 == '1'); ➡️ true
console.log(1 == true); ➡️ true
```
