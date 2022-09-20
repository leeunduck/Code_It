float를 사용할 때에는 3차원적으로 생각을 해야한다

```
div class="blue"></div>
div class="yellow"></div>
div class="orange"></div>
```
이렇게 각각 3개의 요소가 있을 때 위치는 차례대로 채워질 것이다

이 때 blue div를 길이를 줄이고 float을 사용한다면 어떻게 될까?

```
.blue {
  width: 300px;
  float: left;
}
```
blue의 요소는 길이는 300px로 짧아질 것이고 float을 사용했기 때문에 yellow, orange요소보다 더 위에 떠 있을 것이다 

그렇기 때문에 yellow, orange요소가 위로 올라오게 되고 2차원적인 브라우저 상에는 blue와 yellow가 겹쳐 보이는 것처럼 보일 것이다

## float 사용법

뉴스 레이아웃을 사용할 때 (사진에 글이 둘러쌓여져 있는 것처럼 보이는 것)
