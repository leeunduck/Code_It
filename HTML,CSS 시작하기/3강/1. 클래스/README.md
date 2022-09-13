# class

>태그가 같은 태그들 중 하나만 뽑아서 쓰고 싶을 때 class 이용하면 된다

```
<p>첫 번째 문단</p>
<p class="second">두 번째 문단</p>
<p>세 번째 문단</p>
<p>네 번째 문단</p>
```

>class 이름을 이용해서 스타일링을 해줄 수 있다

```
<style>
.second {
  font-size: 64px;
}
</style>
```

>한개의 태그에 여러개 class를 넣고 싶으면

```
<p class="first">첫 번째 문단</p>
<p class="second first">두 번째 문단</p>
<p>세 번째 문단</p>
<p>네 번째 문단</p>
```

띄어쓰기 후 원하는 클래스를 집어 넣으면 된다
