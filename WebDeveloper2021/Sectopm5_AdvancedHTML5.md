### HTML Forms
- Form tag
- input tag: self-closing tag. type attribute
  - text: text box / required - it'll say please fill out, this field.
  - submit: creates a button. don't specify what to say, it'll just have this text('submit'). can change text(with attribute value)
  - reset: reset button. reset form.
  - email: include @ in the email address.
  - date: calendar box
  - radio: radio buttons are family and only one of them can be picked. -> with name attribute
  - checkbox: can select multiples

### HTML Forms2
- select tag: drop-down menu. can use option tag / multiple - can select multiple options
- input tag
  - password: password form. can set chracter length with 'minlength' attribute

### Submitting A Form
- name attribute
- url일부 - ?firstname=fake&lastname=man&email=wo%40bwop.com&password=abwef&birthday=2017-01-01&gender=on&dog=on
- values that we entered, into our form were just attached to this link. -> query strings
- It's one way for us, to send our information to the backend or the servers because we have to store this.
- form was using an attribute called "GET" and "POST"
- "GET": it will attach the form information to the URL and send it to the server
- "POST": wouln't see any query parameters. because it will be attached to the body of the request.
- It starts off,with question mark wich states, coming up, we're going to have a bunch of data for you. corresponds with the name(as property), that we have in our form. and value(input box에 입력하는 값 - ?firstname=fake의 fake부분)
- URL encoding
- (ex)radio-button, checkbox, select box-options - URL ?gender=On - parameter value를 알 수 없음. - value attribute 추가.(명시)

### HTML Tags3
- comment: :"<!-- -->"
- 'div' tag: are used to divide content. it is very powerful when we get into CSS.'div' tag allows us to add styles and divide up the content into each different section, so than, each section of our website, can have its own little box.
- 'span' tag: span is a inline element, so an inline element is different from a block element, 'span' tag we can add it to a specific line. -> we can add some styles only to the "First Name". and we can emphasize it.
- tags that we can use as tools, when we want to have a container, an invisible container, around a piece of element and are HTML

### HTML vs HTML5
- What HTML5 is? - the lates
- There are many evolutions of HTML
- Many websites contain HTML code like:
```HTML
<div id='nav'>
<div class="header">
<div id="footer">
```
to indicate navigation, header, and footer
- HTML offers new semantic elements to define different parts of a web page
- header means, nav means and footer means, give a lot more meaning to the web page and it'll have a better idea of, how the website is structured and where it's their rank and thir Google search results.
- Good to SEO performance
- HTML5 tries to, improve the performance of the web

### Copy a website
- Windows: Ctrl+U - 페이지 소스보기

### HTML Challenge
- send your own website with HTML5

### [HTML Quiz](https://www.w3schools.com/html/html_quiz.asp) - 38/40
- HTML
- Web Standard
- largest heading tag
- break line tag
- add backgroud color
```html
<body style="background-color:yellow;>
```
- important text tag - strong tag
- emphasized text tag - em tag
- creating a hyperlink
- hyperlink in new tab or browser option(a tag)
```html
<a href="url" target="_blank">
```
- table tag elements - table, tr, td
- Inline elements are normally displayed without starting a new line - True
- textarea tag
- inserting background image
```html
<body style="background-image:url(background.gif)">
```
- iframe tag is used to display a web page within a web page - True
- Block elements are normally displayed without starting new linke - False 
- img alt attribute: specifies an alternate text for an image, if the image cannot be displayed
- SVG elements <-In HTML, you can embded SVG elements directly into an HTML page
- contenteditable is global attribute specify wheather the content of an element should be editable or not.
- onblur and onfocus - Event attributes
- XML - format of graphics defined by SVG 
- canvas element is used to draw graphics
- required attribute is used to specify that an input field must be filled out.
- input type - range defines a slider control.
- meter HTML element used to display a scalar measurement within a range
- nav tag HTML element defines navigation links
- aside tag: define content aside from the page content
- video tag
- audio tag
- header tag HTML element is used to specify a header for a document or section
- 추가: [HTML syntaxes](https://www.w3schools.com/html/exercise.asp)

### Optional Exercise: More HTML
- [practice](https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/)