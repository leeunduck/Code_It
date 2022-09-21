제가 부트스트랩을 사용할 때 가장 마음에 드는 점은 간편한 그리드 시스템입니다.

## 기본 구성원
부트스트랩 그리드 시스템에는 세 가지 구성원이 있습니다:

1. 컨테이너 (container)
2. 행 (row)
3. 열 (column)

## 기본 규칙
부트스트랩 사이트에 자세히 설명되어 있지만 많은 분들이 무시하는 몇 가지 규칙입니다:

1. 행(div class="row")은 꼭 컨테이너(div class="container") 안에 넣어주세요.
2. 열(div class="col")은 꼭 행(div class="row") 안에 넣어주세요. 오직 열만 행의 직속 자식이 될 수 있습니다.
3. 콘텐츠(우리가 그리드에 넣고 싶은 내용)는 꼭 열(div class="col") 안에 넣어주세요.

이 규칙들만 지켜도 예상치 못한 레이아웃이 나오지는 않을 것입니다!

## 기본 사용법
구성원들과 규칙을 알았으면 이제 사용법을 알아봅시다.

부트스트랩 그리드에는 한 줄에 기본적으로 12칸의 열(column)이 있다고 생각하시면 됩니다. 
  
예를 들어서 한 줄을 정확히 3등분하고 싶으면 네 칸을 차지하는 열 세 개를 쓰면 되는 거죠. 
  
네 칸을 사용하는 열은 div class="col-4"입니다.

아래의 코드에서는 다양한 방식으로 12칸을 나누어보았습니다.

```
HTML
<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">
</head>

<body>
  <div class="container">
    <div class="row">
      <!-- 정확히 3등분 -->
      <div class="col-4 first">first</div>
      <div class="col-4 second">second</div>
      <div class="col-4 third">third</div>
    </div>

    <div class="row">
      <!-- 정확히 2등분 -->
      <div class="col-6 first">first</div>
      <div class="col-6 second">second</div>
    </div>

    <div class="row">
      <!-- 1대 5 비율 -->
      <div class="col-2 first">first</div>
      <div class="col-10 second">second</div>
    </div>

    <div class="row">
      <!-- 1대 2대 1 비율 -->
      <div class="col-3 first">first</div>
      <div class="col-6 second">second</div>
      <div class="col-3 third">third</div>
    </div>
  </div>
</body>


CSS
.container {
  text-align: center;
}

.first {
  background-color: yellow;
}

.second {
  background-color: lime;
}

.third {
  background-color: orange;
}
```

## 12칸을 넘어가면?
만약 한 행에 12칸이 넘는 열이 들어간다면, 새로운 줄로 넘어가게 됩니다.

```
HTML
<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">
</head>

<body>
  <div class="container">
    <div class="row">
      <div class="col-3 first">first</div>
      <div class="col-6 second">second</div>
      <div class="col-4 third">third</div>
      <div class="col-7 fourth">fourth</div>
    </div>
  </div>
</body>


CSS
.container {
  text-align: center;
}

.first {
  background-color: yellow;
}

.second {
  background-color: lime;
}

.third {
  background-color: orange;
}

.fourth {
  background-color: blue;
}
```

## Why 12?
부트스트랩을 만든 분들은 왜 하필 12라는 숫자로 정했을까요?

12는 상당히 많은 숫자들(1, 2, 3, 4, 6, 12)로 나누어지기 때문에 굉장히 유연합니다!

예를 들어서 8칸으로 나누고 싶더라도 12라는 숫자의 유연함 덕분에 쉽게 할 수 있습니다. 

col-6를 두 개 쓰면 2등분 할 수 있고, 그 안에서 또 col-3로 4등분을 하면 8칸이 생기겠죠?

이런식으로 열을 또 여러 열로 나누는 것을 '중첩(nesting)'한다고 부릅니다. 

중첩을 하기 위해서는 우선 열(div class="col-6") 안에 새로운 행(div class="row")을 쓰셔야 합니다. 
  
예제를 통해 살펴보세요:

```
HTML
<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">
</head>

<body>
  <div class="container">
    <div class="row">
      <div class="col-6">
        <div class="row"> <!-- 중첩을 위한 새로운 행 -->
          <div class="col-3 first">1</div>
          <div class="col-3 second">2</div>
          <div class="col-3 third">3</div>
          <div class="col-3 fourth">4</div>
        </div>
      </div>
      

CSS
.container {
  text-align: center;
}

.first {
  background-color: yellow;
}

.second {
  background-color: lime;
}

.third {
  background-color: orange;
}

.fourth {
  background-color: blue;
}
```
