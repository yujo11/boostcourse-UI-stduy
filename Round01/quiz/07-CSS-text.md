# Mini Project Quiz

## 07. CSS text

word-wrap 속성을 이용해서 띄어쓰기가 없는 긴 단어를 어떻게 처리할지 정할 수 있습니다.

즉, 아래과 같이 문장이 긴 경우라면 문장이 영역을 벗어나 표현되는 경우가 발생합니다.

![](https://github.com/YUJO42/boostcourse-UI-stduy/blob/main/Round01/img/css-text.png?raw=true)

위의 결과를 나타내는 코드가 아래와 같을 때 1번에 들어갈 수 있는 코드를 작성해주세요.

- word-wrap 이 아닌 다른 추가적인 속성을 생각해보세요!!

```html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8" />
    <title>word-wrap</title>
    <style>
      p {
           width : 400px;
           padding: 5px;
           background-color : #ddd;
           word-wrap : normal;
           ____________(1)_____________
       }
    </style>
  </head>
  <body>
    <p>
      loremipsumdolorloremipsumdolorloremipsumdolorloremipsumdolorloremipsumdolor
    </p>
  </body>
</html>
```

### 정답

<details>
<summary>정답 확인하기</summary>
<div markdown="1">

1. word-break: break-all;

</div>
</details>

