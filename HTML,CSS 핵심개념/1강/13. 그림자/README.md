요소에 그림자를 주기 위해서는 box-shadow 속성을 사용하면 되는데요. 기본값은 none입니다. 그림자가 없다는 뜻이죠.

```
.div1 {
  background-color: #eeeeee;
  width: 400px;
  height: 300px;
  box-shadow: none;
}
```

## 그림자 추가
### 위치 설정
그림자의 위치만 설정해주면 그림자가 나타납니다. 가로 위치와 세로 위치를 설정해줍시다.

```
.div1 {
  background-color: #eeeeee;
  width: 400px;
  height: 300px;
  box-shadow: 40px 10px;
}
```

### 그림자 색 설정
위의 예시를 보시면 그림자가 검정색이죠? 따로 설정해주지 않으면 그림자는 검정색입니다. 만약 다른 색으로 바꾸고 싶으면 box-shadow속성에 추가로 색을 써주면 됩니다.

```
.div1 {
  background-color: #eeeeee;
  width: 400px;
  height: 300px;
  box-shadow: 40px 10px #4d9fff;
}
```

### 흐림 정도 (blur)
box-shadow 속성에서 그림자가 얼마나 흐리게 나올지 설정해줄 수 있습니다. 가로, 세로 위치 뒤에 추가해주면 되는데요. 기본값은 0px입니다.

```
.div1 {
  background-color: #eeeeee;
  width: 400px;
  height: 300px;
  box-shadow: 40px 10px 10px #4d9fff;
}
```

### 그림자 크기 (spread)
그림자가 얼마나 퍼질지도 설정할 수 있습니다. 흐림 값 이후에 써주면 됩니다.

```
.div1 {
  background-color: #eeeeee;
  width: 400px;
  height: 300px;
  box-shadow: 40px 10px 10px 20px #4d9fff;
}
```
