# Mini Project Quiz

## 03. HTML From

테이블을 구성하는 방법에는 강의에서 학습한 내용 외에 다른 방법도 있습니다.

다음 빈 칸을 채워 아래와 같은 결과가 나올 수 있도록 코드를 작성해보세요.

![](https://github.com/YUJO42/boostcourse-UI-stduy/blob/main/Round01/img/form.png?raw=true)

```html
<form>
   <h1>이메일</h1>
   <fieldset>
      <legend>메일 정보</legend>
      _________________________(1)___________________________ <br>
      <label for="cc">참조 : </label> <input type="email" placeholder="aaa@naver.com"id="cc"><br>
      <label for="title">제목 : </label> <input type="____(2)____" id="important"><br>
      <label for="____(3)____">중요!</label> <input type="text" id="title"><br>
      <label for="file">파일첨부 : </label> <input type="file" id="file"><br>
   </fieldset>
   <fieldset>
      <legend>메일 내용</legend>
      <textarea _____(4)_____ placeholder="자기소개는 짧게 해주세요."></textarea><br>
      <button type="submit">전송</button>
      <butoon _____(5)_____>취소</button>
   </fieldset>
</form>

```

### 정답

<details>
<summary>정답 확인하기</summary>
<div markdown="1">

1. `<label for="receiver">받는 사람 : </label>`
2. `<label for="title">제목 : </label>`
3. `<input type="checkbox" id="important" />`
4. `<textarea cols="100" rows="30" placeholder="자기소개는 짧게 해주세요."></textarea>`

</div>
</details>
