# 객체와 메소드

```
let greetings = {
  sayHello: function () {
    console.log('Hello!');
  },
  sayHi: function () {
    console.log('Hi!');
  },
  sayBye: function() {
    console.log('Bye');
  }
};

greetings.sayHello();
```

```
파라미터가 필요한 경우

let greetings = {
  sayHello: function (name) {
    console.log(`Hello! ${name}`);
  },
  sayHi: function () {
    console.log('Hi!');
  },
  sayBye: function() {
    console.log('Bye');
  }
};

greetings.sayHello('unducklee');

greetings['sayHello']('unducklee');

➡️ Hello unducklee!
```

>메소드는 어떤 객체의 고유한 동작으로서 함수에 의미를 부여할 수 있기 때문
