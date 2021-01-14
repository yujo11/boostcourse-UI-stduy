# Mini Project Quiz

## 08. CSS position

position 속성을 사용해 아래의 화면을 구현하고자 합니다.

아래의 화면에서 볼 수 있듯이 스크롤을 내려도 상단바는 움직이지 않는데요, (페이스북의 상단바를 생각하면 쉽습니다)

지금까지 배운 내용들을 종합하여 빈칸의 코드를 작성해주세요.

결과)

![](https://github.com/YUJO42/boostcourse-UI-stduy/blob/main/Round01/img/css-position.png?raw=true)

```html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="UTF-8" />
    <title>position</title>
    <style>
      header {
        position: __(1) __;
        top: __(2) __;
        left: 0;
        right: __(3) __;

        height: 75px;
        padding: 1 __(4) 단위__;
        color: white;
        background: teal;
      }

      h1,
      p {
        margin: 0;
      }

      body,
      html {
        height: 200%;
      }

      * {
        ____(5)____: border-box;
      }
    </style>
  </head>
  <body>
    ______(6)______
    <h1>고정된 영역</h1>
    ______(6)______
  </body>
</html>
```

### 정답

<details>
<summary>정답 확인하기</summary>
<div markdown="1">

1. fixed
2. 0
3. 0
4. em
5. box-sizing
6. <header></header>

</div>
</details>
