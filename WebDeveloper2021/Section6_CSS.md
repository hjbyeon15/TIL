### Your First CSS
- inner designer <-CSS
- link to style sheet(CSS file)
- link tag allows us to link this html file to somthing else
- rel: stylesheet, type: media type, href: link address
- cascading means that it always take the selector that is at the end and that's simplified terms but I want to demonstrate for you what that means.
- trickles down and cascades
```css
/*해당 스타일을 적용한 페이지의 <p>값 색상은 그린으로 보여짐. */
h2 {
    color: red;
}
p {
    color: pink;
}
p {
    color: green;
}
```
- inline style and others.(CSS(style) 사용 방법)
```css
/*1. CSS 파일 생성 - link 연결*/
<link rel="stylesheet" type="text/css" href="style.css">
/*2. inline style: tag element에 포함*/
<header style="background-color: green; color:red;">
/*3. Style(CSS) 자체 삽입*/
<style>
    li {
        background-color: purple;
        color: white;
    }
</style>
```
- web sites bigger and massive. CSS code more and more. -> seperate CSS
- HTML just worry abount text, CSS just worry about styles.
- seperation of concerns
### CSS Properties
- properties: we want to change within a web page
- 참고: [CSS Tricks](https://css-tricks.com/almanac/)
- specific we trickle down to smaller elements.
- [bunch of colors](https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF)
- hex,rgb,rgba etc...
- rgba - 4th elements -> transparent(?).
### CSS Selectors
- CSS Cheat Sheet
  - https://www.w3school.com/cssref/css_selectors.asp
  - https://css-tricks.com/almanac/
- Cascading Style Sheets at the most basic level it indicated that the order of CSS rules matter.
- .class is a good way to select a group of elements and make sure that they all have same things
- #id is similar to class except for you can use the same ID only once
- * is not used very often but it symbolizes all elements. often use in the top
### Optional Exercise: CSS Selectors(article)
### Text and Font
### Images In CSS
### Box Model
### px vs em vs rem
### Exercise: CSS Quiz
