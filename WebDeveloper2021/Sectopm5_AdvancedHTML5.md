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