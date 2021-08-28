# Frontend

## 참고링크

https://www.w3schools.com/

https://codesandbox.io/s/itac-08-0ye9v?file=/index.html
https://github.com/edu-ministori/frontend_08

https://codesandbox.io/
https://jsbin.com/
https://developer.mozilla.org/

## HTML

### Introduction

https://www.w3schools.com/html/html_intro.asp

> 웹 페이지 구조 표시

> 웹 페이지 콘텐츠 표시
>
> - 텍스트 콘텐츠
> - 멀티미디어 콘텐츠 : 이미지, 비디오, 오디오

#### HTML Element

https://www.w3schools.com/html/html_elements.asp

`(backtick)

```
<tagname>Contents</tagname>
* 시작태그만 있는 경우 : Empty Element
```

> 포함관계(nested)

```
<html>
  <body>
    <h1>Heading</h1>
  </body>
</html>
```

> html-body-h1 관계
>
> html : body와 관계 - 부모요소 / h1과 관계 - 조상요소
>
> body : h1과 관계 - 부모요소 / html과 관계 - 자식요소
>
> h1 : body와 관계 - 자식요소 / html과 관계 - 자손요소

### HTML Attribute

https://www.w3schools.com/html/html_attributes.asp

### HTML Headings

https://www.w3schools.com/html/html_headings.asp

h1~h6 : 제목태그(h -> heading)

### HTML Paragraph

https://www.w3schools.com/html/html_paragraphs.asp

### HTML Link

https://www.w3schools.com/html/html_links.asp

a : anchor

> URL(Uniform Resource Locator) : 파일식별자(위치표시>, 가장 넓은 의미의 인터넷 주소
> 인터넷 주소
>
> - IP(Internet Protocal) : 숫자로 구성된 주소(192.168.0.1)
> - Domain Name : www.naver.com / DNS(Domain Name Server)
> - Ex) blog.naver.com/blog/12345 => URL

### HTML File 경로

https://www.w3schools.com/html/html_filepaths.asp

절대Absolute File Paths vs 상대 Relative File Paths

- 경로 위치 표시 방식
- 경로 표시의 기준의 변경 여부
- 절대 경로 방식
- Ex) 대한민국 서울특별시 서초구 동 대호빌딩 801호 -절대경로
- 출발지위치에 상관없이 항상 찾아갈 수 있도록 표시
- Ex) 도메인주소/상세경로(URL) => http://www.naver.com/blog/image.jpg

- 상대 경로 방식
- Ex) 강남역 11번출구에서 3분 올리오시면 대호빌딩 - 상대표시방식 강남역을 모르는 사람은 찾아올 수 없다
- 출발지 위치를 기준으로 표시
- Ex) 상세경로 => /blog/image.jpg || inage.jpg

### HTML List

https://www.w3schools.com/html/html_lists.asp

> 중첩목록(Nested List)

### HTML Table

https://www.w3schools.com/html/html_tables.asp
Table generator : https://www.tablesgenerator.com/

### HTML Images

https://www.w3schools.com/html/html_images.asp

alt : alternative

### HTML Video

https://www.w3schools.com/html/html5_video.asp

### HTML Youtube

https://www.w3schools.com/html/html_youtube.asp
? 실제 기호와 주소 구분 & 추가 autoplay =1"

https://freebiesbug.com/psd-freebies/website-template/

### HTML Block & inline

https://www.w3schools.com/html/html_blocks.asp

> 영역의 특성

> - 블럭요소 : 가로길이 - 부모요소에 채워짐 / 세로길이 - 자식요소에 맞춰짐.
> - 인라인 요소 : 가로길이와 세로길이 모두 자식요소에 맞춰짐

> 포함관계
>
> - 블럭요소 : 다른 블럭요소, 인라인 요소, 콘텐츠 포함 가능
> - 인라인 요소 : 다른 인라인 요소, 콘텐츠 포함 가능, 블럭요소는 포함 불가능
> - 예외 : a - 인라인 요소이지만 블럭 요소를 포함 가능

### HTML Id & Class

https://www.w3schools.com/html/html_id.asp

https://www.w3schools.com/html/html_classes.asp

> id attribute
>
> - id로 붙여주는 이름은 한 HTML 문서내에서 고유해야 함.(한번만 사용)
> - id는 한 대상의 HTML Element에 하나의 이름만 지정할 수 있음.

> class attribute
>
> - class로 붙여주는 이름은 한 HTML문서내에서 여러번 중복 사용할 있음.
> - class는 한 대상의 HTML Element에 여러개의 이름을 지정할 수 있음.

### CSS 상속

> 부모요소에 적용된 CSS속성이 자식요소에 적용되는 것을 상속이라고 함(모든것은아님)

### CSS Text

https://www.w3schools.com/css/css_text.asp

> - color
> - text-align
> - text-decoration
> - letter-spacing
> - line-height

### CSS Fonts

https://www.w3schools.com/css/css_font.asp

### Web Fonts

> Web Font

> 웹에서 사용하는 폰트는 브랑누저에서 랜더링되기 때문에 기존에는 사용자 PC에 설치되어있는 폰트를 사용

> 사용자 PC에 설치된 폰트를 찾지 않고 서버에 폰트를 저장해서 사용하는 방식 => 웹폰트 방식

> 웹폰트 서비스
>
> - 구글 폰트(영문/한글) : https://fonts.google.com/
> - 눈누 폰트(한글) : https://noonnu.cc/font_page/630

> Font-family
>
> - 항상 폰트 목록 끝에 기본 폰트 이름을 입력해야 함.
> - 고딕 : sans-serif / 명조 serif
>
> font-size
>
> font-style : italic
>
> font- weight
>
> - 100, 200, 300 ... : 숫자로 표시

### CSS Links
