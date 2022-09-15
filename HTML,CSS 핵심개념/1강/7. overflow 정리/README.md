width, height, max-width, max-height 등을 설정하다 보면 내용물이 들어갈 공간이 부족한 경우가 있습니다.


```
p {
  border: 1px solid blue;
  width: 300px;
  height: 200px;
}
```

이렇게 넘쳐나는 내용물을 overflow 속성으로 처리해줄 수 있는데요. 몇 가지 옵션이 있습니다.

## 옵션 1: visible
visible 값을 사용하면 넘쳐나는 내용물이 그대로 보입니다. 따로 설정해주지 않으면 이게 기본값입니다!

```
p {
  border: 1px solid blue;
  width: 300px;
  height: 200px;
  overflow: visible;
}
```

## 옵션 2: hidden
hidden 값을 사용하면 넘쳐나는 부분을 아예 숨겨줄 수도 있습니다.

```
p {
  border: 1px solid blue;
  width: 300px;
  height: 200px;
  overflow: hidden;
}
```

## 옵션 3: scroll
내용물을 숨겼다가, 사용자가 스크롤을 하면 볼 수 있게 해주는 방법도 있습니다!

```
p {
  border: 1px solid blue;
  width: 300px;
  height: 200px;
  overflow: scroll;
}
```

## 옵션 4: auto
scroll과 거의 똑같은데, 한 가지 차이점이 있습니다. scroll은 항상 스크롤바를 보여주고, auto는 내용물이 넘쳐날 때만 스크롤바를 보여줍니다.

 
참고로 Mac OS에서는 스크롤을 할 때만 스크롤바를 보여주는 경향이 있기 때문에 scroll과 auto의 차이를 보기 힘들 수도 있습니다.

```
p {
  border: 1px solid blue;
  width: 300px;
  height: 200px;
  overflow: auto;
}
```
