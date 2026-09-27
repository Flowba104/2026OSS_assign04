# Form 실습 과제

## 1. Key Learning

이번 주 실습을 통해 배운 핵심 내용입니다.

### 1) HTML Form의 기본 구조
- `<form>` 태그의 역할
- `<label>`과 `<input>`을 연결하는 방법
- `id`, `name`, `value` 속성의 역할

### 2) 다양한 Form Element 사용
- text, checkbox, radio 등의 `<input>` 사용
- `<select>`와 `<option>`을 이용한 선택 목록 구현
- `<textarea>`를 이용한 여러 줄 입력 구현

### 3) CSS를 이용한 Form 디자인
- `border`, `padding`, `margin` 등을 이용한 Form 디자인
- `:focus`, `:hover`를 이용한 상태 변화 구현
- HTML 구조와 CSS 스타일의 역할 차이 이해


## 2. Form Elements

이번 과제에서 사용한 Form 요소와 각각의 용도입니다.

| Form Element | 용도 |
|---|---|
| `<form>` | 사용자 입력 요소들을 하나의 Form으로 구성해준다 |
| `<input type="text">` | 텍스트를 입력받는다 |
| `<input type="checkbox">` | 여러 옵션을 선택할 수 있으며 하나만 선택하지 않는다는 점에서 radio랑 차이를 보인다|
| `<input type="radio">` | 여러 항목 중 하나를 선택한다 |
| `<input type="submit">` | Form을 제출한다 |
| `<select>` | 드롭다운 목록 생성 |
| `<option>` | select 내부의 선택 항목 생성 |
| `<textarea>` | 여러 줄의 텍스트 입력 |
| `<label>` | 각 입력 요소에 대한 설명 제공 |


## 3. HTML vs CSS

### form1.html

- HTML을 중심으로 Form의 구조를 작성했습니다.
- `input`, `select`, `radio`, `checkbox` 등의 Form Element를 사용했습니다.
- 각 입력 요소의 의미와 배치에 집중했습니다.

### form1_css.html

- form1.html의 Form 구조에 CSS를 추가했습니다.
- `color`, `background-color`, `border`, `border-radius` 등을 이용해 디자인했습니다.
- `padding`, `margin`, `width`를 이용해 크기와 간격을 조절했습니다.
- `:focus`, `:hover`를 이용해 사용자 동작에 따른 변화를 추가했습니다.


## 4. Problem & Solution

### Problem 1
Form을 만들면서 First name과 Last name, Expiration과 CVV처럼 서로 관련된 입력 칸들을 어떻게 배치해야 자연스럽게 보일지 고민했습니다. 모든 입력 요소를 한 줄씩 배치하면 Form이 너무 길어지고 실제 웹사이트의 Form과도 차이가 있었습니다. 


### Solution
서로 관련된 입력 요소들을 <div>로 묶어 한 영역에 배치했습니다. 또한 width, margin, padding 등을 조절하면서 입력 칸의 크기와 간격을 조절했습니다. 이를 통해 Form의 요소들을 목적에 따라 묶어서 배치하는 방법을 알게 되었습니다.


## 5. Reflection

### 새롭게 알게 된 점

작성: 각종 element에 대해서 배울 수 있었고 어떻게 CSS를 자연스럽게 넣을 수 있을지 알게 되었습니다.
다음에는 이번에 배운 것을 토대로 어떨때 field set을 쓰면 유리할지 실전에서 사용해보고 싶다는 생각이 들었습니다.


### 궁금한 점

작성: 언제 fieldset을 쓰며 어떨 때 써야 깔끔한지 궁금하였습니다.