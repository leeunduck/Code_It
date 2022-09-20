# multiple floats

```
div class="blue"></div>
div class="yellow"></div>
div class="orange"></div>
```

```
.blue {
  width: 300px;
  float: left;
}
.yellow {
  width: 300px;
  float: right;
}
```
위와 같이 두개를 띄우게 되면 차례대로 인식이 된다 처음 blue요소가 띄워지고 나머지 요소들은 blue자리에 채워지게 된다 그 다음 yellow요소가 오른쪽에 띄워지고 나머지 orange요소가 올라오게 된다

```
.blue {
  width: 300px;
  float: right;
}
.yellow {
  width: 300px;
  float: right;
}
```
만약 float의 방향이 같다면 blue자리가 먼저 오른쪽으로 채워지고 yellow요소는 파란색 왼쪽에서 멈추게 된다

## 그리드 (Grid)

사이트의 내용을 정리하는 가로, 세로 틀
