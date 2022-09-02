# 라이브러리

마치 도서관에서 필요한 책을 찾아보듯 필요한 코드를 찾아서 쓸 수 있게 해둔 것

>내가 만들고 싶은 기능에 상당 부분이 다른 사람이 만든 기능과 유사할 수 있다

>기존의 코드에서 필요한 코드를 추가하니 프로그램을 만드는 속도가 훨씬 빨라졌다

>언어마다 자신에게 맞는 라이브러리가 있다
원하는 라이브러리가 Python에 없고 Java에 있다면 어쩔 수 없이 Java를 사용해야 한다

```
import pandas as pd
import seaborn as sns

df = pd.read_csv("data/movie_genres.csv")
sns.clustermap(dr.corr())
```
