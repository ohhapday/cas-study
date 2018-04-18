# 태그 종류
[자주 사용되는 태그 통계](https://www.advancedwebranking.com/html/)

[공식문서](https://developer.mozilla.org/ko/docs/Web/HTML/HTML5)

1. [Doctype (기본요소)](https://developer.mozilla.org/ko/docs/Web/HTML/Element#%EA%B8%B0%EB%B3%B8_%EC%9A%94%EC%86%8C)

2. [Basic elements and metadata (문서 메타데이터)](https://developer.mozilla.org/ko/docs/Web/HTML/Element#%EB%AC%B8%EC%84%9C_%EB%A9%94%ED%83%80%EB%8D%B0%EC%9D%B4%ED%84%B0https://developer.mozilla.org/ko/docs/Web/HTML/Element#%EB%AC%B8%EC%9E%90_%EC%BD%98%ED%85%90%EC%B8%A0)

3. [Content sectioning (컨텐츠 구획화)](https://developer.mozilla.org/ko/docs/Web/HTML/Element#%EC%BB%A8%ED%85%90%EC%B8%A0_%EA%B5%AC%ED%9A%8D%ED%99%94)

4. [Text content (문자 콘텐츠)](https://developer.mozilla.org/ko/docs/Web/HTML/Element#%EB%AC%B8%EC%9E%90_%EC%BD%98%ED%85%90%EC%B8%A0)

5. [Inline text semantics (인라인 텍스트 시멘틱)](https://developer.mozilla.org/ko/docs/Web/HTML/Element#%EC%9D%B8%EB%9D%BC%EC%9D%B8_%ED%85%8D%EC%8A%A4%ED%8A%B8_%EC%8B%9C%EB%A9%98%ED%8B%B1)

6. [Image and multimedia (이미지 & 멀티미디어)](https://developer.mozilla.org/ko/docs/Web/HTML/Element#%EC%9D%B4%EB%AF%B8%EC%A7%80_%EB%A9%80%ED%8B%B0%EB%AF%B8%EB%94%94%EC%96%B4)

7. [Table content (표 콘텐츠)](https://developer.mozilla.org/ko/docs/Web/HTML/Element#%ED%91%9C_%EC%BD%98%ED%85%90%EC%B8%A0)

8. [Forms (폼)](https://developer.mozilla.org/ko/docs/Web/HTML/Element#%ED%8F%BC)

9. 기타 - 내장 콘텐츠, 스크립팅, 수정, 대화형 요소, 웹 컴포넌트


## Content sectioning - 컨텐츠 구획화
>
> ![구성](http://cfile9.uf.tistory.com/image/261BFE435539390B1BBF48)
> #### 콘텐츠 섹션 요소를 사용하면 콘텐츠를 논리적 조각으로 구성 할 수 있습니다.

### 1. 주요 태그
- [`<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`](https://developer.mozilla.org/ko/docs/Web/HTML/Element/Heading_Elements)
- [`<section>`](https://developer.mozilla.org/ko/docs/Web/HTML/Element/section)
- [`<article>`](https://www.w3schools.com/tags/tag_article.asp)

### 2. 예시
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>title</title>
</head>
<body>
  <header></header>
  <nav></nav>
  <section>
    <article>
      <h1></h1>
      ...
    </article>
  </section>
  <aside></aside>
  <footer></footer>
</body>
</html>
```

***    

## 최근 Design 추세
 * Material Design
   * Depth 표현

Name | Lunch order | Spicy      | Owes
---- | ----------- | ---------- | ----:
Joan | saag paneer | medium     | $11
Sally| vindaloo    | mild       | $14
Erin | lamb madras | HOT        | $5
