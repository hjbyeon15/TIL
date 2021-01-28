## 01.HTML&CSS 첫걸음/개요
### HTML
- Hyper Text Markup Language
- 제목,문단,표 등을 정의하고, 구조와 의미를 부여하는 정적 언어.
- 웹의 구조(뼈대)를 만드는 것(구조화,Semantic)

### CSS
- Cascading Style Sheet
- 마크업 언어(HTML,XML 등)가 표시되는 방법(ex.색상,크기,폰트,레이아웃 등)
- 꾸며주는 역할(웹의 시각적 표현 담당)의 정적 언어

### JS(JavaScript)
- 콘텐츠를 바꾸고 움직이는 등 페이지를 동적으로 꾸며주는 역할을 하는 프로그래밍 언어
- HTML,CSS 역할로 활용 가능하나 성능적으로 좋지 않으므로 동적 처리에 집중 하는 것이 좋음.

> 유지보수,확장성,생산성을 위해 언어의 역할에 맞게 웹을 구성. 구조적,기술적으로 최적화

### 웹 표준(Web Standard)
- 웹에서 사용되는 표준 기술이나 규칙
- W3C
- 웹 표준 기반 웹 브라우저들(Chrome,IE,Safari 등)
- 만드는 업체, 표준 기술을 해석하는 차이, 새로운 기술 삽입 등으로 인한 브러우저 별 차이 발생
- ActiveX, Flash와 같은 기술은 표준이 아님.(특정 회사의 기술)
- [표준화 제정 단계](https://wit.nts-corp.com/2013/10/16/280)
- 

### 크로스브라우징(Cross Browsing)
- 다르게 구동되는 여러 브라우저에서 동일한 사용자 경험을 제공할 수 있도록 제작하는 방법 혹은 기술

### 웹 접근성
- 웹을 쓸 수 있는 누구나 쉽게(동등하게) 웹 사이트를 사용할 수 있도록 해야한다.
- [웹접근성연구소](https://www.wah.or.kr:444/Accessibility/define.asp)
- [한국형웹콘텐츠접근성지침](https://www.wah.or.kr:444/Participation/guide.asp)
- [웹콘텐츠제작기법](https://www.wah.or.kr:444/Participation/technique.asp)

### 웹 개발을 위한 에디터
- 크로스 플랫폼(Windows, MacOS 공통 사용가능) 에디터
- Sublime Text: 상대적으로 가벼움.
- Atom: Github에서 만든 텍스트 에디터
- Brackets: Adobe에서 만든 오픈소스 에디터. Live Preview 기능 기본 제공. 성능 최적화 아쉬움.
- VS Code(VisualStudio Code): MS(마이크로소프트)에서 만든 텍스트 에디터. 확장 기능이 매우 많음.
- WebStorm: JetBrain에서 만드는 통합개발환경(IDE) 프로그램
- 별도의 확장 프로그램 설치 없이 에디터 하나만으로 모든 기능 사용 가능
- 유료.

### Visual Studio Code 확장기능(Extensions)
- Korean Language Pack for Visual Studio Code
- Beautify: 코드 가독성을 위해 코드 작성스타일을 수정. 입문자에게 추천
- Live Server
- Auto Rename Tag: 태그 명 수정 시, 자동으로 열린 태그 닫힌 태그 모두 수정됨.

### 웹에서 사용하는 이미지
- 이미지는 비트맵 방식, 벡터 방식
- 비트맵(Bitmap):픽셀이 모여 만들어진 정보의 집합.
- 레스터 이미지(Raster)
- 픽셀단위로 화면에 렌더링
- 벡터(Vector)
- 수학적 정보의 형태들이 만들어내느 결과물
- 점,선,면,위치(좌표),색상정보 등 정보를 온전하게 가지며, 렌더링(Rendering) 함.
- 수학적 정보만을 가지므로, 이미지 확대/축소에 따른 용량 변화가 없음.
  
### 이미지
- JPG(JPEG,Joint Photogranph coding Experts Group):높은 압축률(적은 용량) - 손실 압축
- PNG(Protable Network Graphics): Gif 대체 포맷으로 개발됨. 비손실 압축. W3C 권장 포맷. 투명도 지원
- Gif(Graphics Interchange Format): 이미지 파일 내에 이미지 및 문자열 같은 정보들을 저장할 수 있음. 비손실 압축. 8비트(256) 컬러만 지원.
- WEBP: JPG,PNG,GIF의 대체 포맷(구글)
- SVG(Scalable Vector Graphics): 마크업 언어(HTML,XML 등)기반의 벡터 그래픽을 표현하는 포맷. 해상도 영향에서 자유로움.JS로 Event Handling 가능(쉽지는 않음).코드와 파일로 확인 가능

### 특수 기호
|기호|발음|한글
|---|-----|---|
|`|Grave(그레이브)|-|
|~|Tilde(틸드)|물결표시|
|!|Exclamation(엑스클러메이션) mark|느낌표|
|@|At(엣) Sign|골뱅이|
|#|Number(넘버)Sign,Sharp(샵)|샵,우물 정|
|$|Dollar Sign|달러|
|%|Percent|퍼센트|
|^|Caret(캐럿)|-|
|&|Ampersand(엠퍼센드)|-|
|*|Asterisk(에스터리스크)|별표|
|-|Hyphen(하이픈),Dash(대쉬)|마이너스|
|_|Underscore(언더스코어),Low Dash(로대쉬)|밑줄|
|"|Quotation(쿼테이션) mark|큰 따옴표|
|'|Apostrophe(아포스트로피) mark|작은 따옴표|
|:|Colon(콜론)|땡땡이|
|;|Semicolon(세미콜론)|털 달린 땡땡이|
|.|Period(피리어드),Dot(닷)|점,마침표|
|/|Slash(슬래쉬)|-|
|'|'|Vertical bar(버티컬)|-|
|()|Parenthesis(퍼렌서시스)|(소)괄호|
|{}|Brace(브레이스)|중괄호|
|[]|Bracket(브래킷)|대괄호|
- [HTML Entity List](https://www.freeformatter.com/html-entities.html) 

### 오픈 소스와 라이선스
- 오픈 소스: 어떤 제품을 개발하는 과정에 필요한 소스 코드나 설계도를 누구나 접근해서 열람할 수 있도록 공개하는 것.
- 개인적 이용은 가능하나, 상업적 이용에 제한 있음.
- Apache License
- MIT License
- BSD License
- Beerware
