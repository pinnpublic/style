# 수업용 CSS Framework

This is a class library repository.

<br>

## Demo

- [데모페이지(기본)](http://pinnpublic.dothome.co.kr/cdn/template.html)
- [데모페이지(테마)](http://pinnpublic.dothome.co.kr/cdn/template-theme.html)
- [데모페이지(글꼴)](http://pinnpublic.dothome.co.kr/cdn/template-font.html)

<br>

## Visual Studio Code Extension

Visual Studio Code > Extensions > `수업용 CSS Framework` 검색 > 설치

[확장프로그램 상세페이지](https://marketplace.visualstudio.com/items?itemName=pinnpublic.classroom-css-framework)

- 테마 클래스 자동완성 지원
- 폰트 CSS URL 자동완성 지원
- 버튼 클래스 자동완성 지원

<img width="582" height="483" alt="Image" src="https://github.com/user-attachments/assets/08a6f255-a892-40d5-a3ff-96d0d0f9da32" />
<br><br>

<br>

## CDN

Copy the following code and add it to the &lt;head&gt; tag of your HTML document.

```html
<link rel="stylesheet" href="http://bit.ly/3WJ5ilK" />
```

Copy the following code and add it before the &lt;/head&gt; tag in the HTML document.

```html
<script src="https://bit.ly/4cMuheh"></script>
```

<!--
Copy the following code and add it to the &lt;head&gt; tag of your HTML document.

```html
<link rel="stylesheet" href="http://pinnpublic.dothome.co.kr/cdn/example-min.css">
```

Copy the following code and add it before the &lt;/head&gt; tag in the HTML document.
```html
<script src="http://pinnpublic.dothome.co.kr/cdn/example-min.js"></script>
```
-->

<!--
full version
&lt;link rel="stylesheet" href="https://me2.do/xmPHeA6J"&gt;

<link rel="stylesheet" href="https://me2.do/5BvBFJ57">
-->

<br>

## Google Icons

https://fonts.google.com/icons

<br>

## Usage

### Basic

- 구글 아이콘 기본 적용(https://fonts.google.com/icons)
- 웹 폰트 기본 적용(GmarketSansMedium)
- 문서는 다양한 너비를 지원하며 중앙 정렬함
- 반응형 지원 안함

### Document Basic Structure

```html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Title</title>
    <link rel="stylesheet" href="http://bit.ly/3WJ5ilK" />
    <style></style>
  </head>
  <body>
    <!--  -->
    <h1>Main Title <small>Sub Title</small></h1>

    <div>Contents</div>

    <script src="https://bit.ly/4cMuheh"></script>
    <script></script>
  </body>
</html>
```

<img width="800" border="1" style="border: 1px solid #777; padding: 1px; outline:10px solid blue;" alt="Image" src="https://github.com/user-attachments/assets/15d9f99a-1742-483f-8c8c-8b271014e7d6" />

<br><br>

### Theme

테마를 지정한다.

- `<html>`: 기본 테마(white)
- `<html class="theme-white">`: 화이트 테마(기본 테마)
- `<html class="theme-black">`: 다크 테마
- `<html class="theme-red">`: 레드 테마
- `<html class="theme-yellow">`: 옐로우 테마
- `<html class="theme-blue">`: 블루 테마
- `<html class="theme-green">`: 그린 테마
- `<html class="theme-purple">`: 퍼플 테마

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/23425bb2-d511-4683-968f-c30ae0a33a2d" />
<br><br>

### Font

글꼴을 지정한다.

- `<link rel="stylesheet" href="https://bit.ly/3WJ5ilK">`: G마켓 산스
- `<link rel="stylesheet" href="https://bit.ly/43wYlI6">`: 넥슨 배찌체
- `<link rel="stylesheet" href="https://bit.ly/4kAXDQZ">`: 빙그레체
- `<link rel="stylesheet" href="https://bit.ly/4kDRN1l">`: 빙그레체 II
- `<link rel="stylesheet" href="https://bit.ly/3H8UpWu">`: 꾸불림체
- `<link rel="stylesheet" href="https://bit.ly/4kkTdOn">`: 카페24 클래식타입
- `<link rel="stylesheet" href="https://bit.ly/3HaJfAl">`: 쿠키런
- `<link rel="stylesheet" href="https://bit.ly/4mwYvrA">`: 온글잎 콘콘체
- `<link rel="stylesheet" href="https://bit.ly/3FuDhK7">`: 독립체
- `<link rel="stylesheet" href="https://bit.ly/4kfEkNi">`: 도스고딕
- `<link rel="stylesheet" href="https://bit.ly/4muHqys">`: EBS훈민정음
- `<link rel="stylesheet" href="https://bit.ly/43wGW2b">`: 펀플로생존자
- `<link rel="stylesheet" href="https://bit.ly/4dxr6Jl">`: 강원교육모두체
- `<link rel="stylesheet" href="https://bit.ly/4jmDmxs">`: 강원교육새음체
- `<link rel="stylesheet" href="https://bit.ly/3FmtfuM">`: 가나초콜릿체
- `<link rel="stylesheet" href="https://bit.ly/4jmDsoO">`: 이사만루
- `<link rel="stylesheet" href="https://bit.ly/3HohxjD">`: 고운돋움
- `<link rel="stylesheet" href="https://bit.ly/4kbcQZd">`: 고양체
- `<link rel="stylesheet" href="https://bit.ly/3Z0kFII">`: 경기천년제목
- `<link rel="stylesheet" href="https://bit.ly/3Fhauc5">`: 학교안심 칠판지우개
- `<link rel="stylesheet" href="https://bit.ly/43GLNz3">`: 학교안심 둥근미소
- `<link rel="stylesheet" href="https://bit.ly/3FaGgYi">`: HS산토끼체2.0
- `<link rel="stylesheet" href="https://bit.ly/4dHaJKk">`: IM혜민체
- `<link rel="stylesheet" href="https://bit.ly/43IVkpb">`: KCC무럭무럭체
- `<link rel="stylesheet" href="https://bit.ly/3F8nkcJ">`: 경북대진리체
- `<link rel="stylesheet" href="https://bit.ly/43xiVrW">`: 교보손글씨
- `<link rel="stylesheet" href="https://bit.ly/44N5MNA">`: 롯데리아 촵땡겨체
- `<link rel="stylesheet" href="https://bit.ly/43wZiQG">`: 마비옛체
- `<link rel="stylesheet" href="https://bit.ly/43pGAdz">`: 망고보드 또박체
- `<link rel="stylesheet" href="https://bit.ly/3Skp7yg">`: 넥슨 메이플스토리
- `<link rel="stylesheet" href="https://bit.ly/3Shzraf">`: 마포배낭여행
- `<link rel="stylesheet" href="https://bit.ly/4kDT3BB">`: 마포홍대프리덤
- `<link rel="stylesheet" href="https://bit.ly/3HnQUeI">`: 나눔스퀘어라운드
- `<link rel="stylesheet" href="https://bit.ly/3H9Pnc6">`: 오뮤 다예쁨체
- `<link rel="stylesheet" href="https://bit.ly/4jl2yV0">`: 원스토어 모바일POP체
- `<link rel="stylesheet" href="https://bit.ly/4kB5TR4">`: 프리텐다드
- `<link rel="stylesheet" href="https://bit.ly/4kfFwQM">`: 정묵바위체
- `<link rel="stylesheet" href="https://bit.ly/3SOYbqu">`: 신라문화체
- `<link rel="stylesheet" href="https://bit.ly/4kuSJEV">`: 어비 세현체
- `<link rel="stylesheet" href="https://bit.ly/4dyC8xY">`: 여기어때 잘난체
- `<link rel="stylesheet" href="https://bit.ly/4dy3156">`: Y최애체
- `<link rel="stylesheet" href="https://bit.ly/45naIJ9">`: 윤초록우산어린이 만세

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/62e55a90-8901-45bf-8d5f-f692f18cbfad" />
<br><br>


### Body

문서 너비를 조절한다.

- `<body>` : 800px
- `<body class="narrow">` : 500px
- `<body class="wide">` : 1200px
- `<body class="w너비">` : 300px ~ 2100px
- `<body class="w300">` : 300px
- `<body class="w1800">` : 1800px

```html
<body>
  <!-- 기본 너비 -->
  <body class="narrow">
    <!-- 500px -->
    <body class="w800">
      <!-- 800px -->
    </body>
  </body>
</body>
```

### Header

헤더를 표시한다.

- `<header class="in">` : 아이콘(로그인 표시)
- `<header class="sticky">` : 화면 고정

```html
<header>
  <h1>Title</h1>
  <ul>
    <!-- 메인 메뉴 -->
    <li><a href="">menu</a></li>
    <li><a href="">menu</a></li>
    <li><a href="">menu</a></li>
    <li>menu</li>
    <li>menu</li>
  </ul>
</header>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/5fabd6cf-e2cd-4f24-a269-562fbf4a20b1" />
<br><br>


```html
<header>
  <h1>Title</h1>
  <ul>
    <!-- 메인 메뉴 -->
    <li><a href="">menu</a></li>
    <li><a href="">menu</a></li>
    <li><a href="">menu</a></li>
    <li>menu</li>
    <li>menu</li>
  </ul>
  <ul>
    <!-- 서브 메뉴 -->
    <li><a href="">sub</a></li>
    <li><a href="">sub</a></li>
    <li>sub</li>
  </ul>
</header>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/2dd39409-7292-449b-94ea-d86be952c054" />
<br><br>


### Heading

제목을 표시한다.

- 1단계 제목
  - `<h1>Title</h1>`
  - `<h1>Title <small>Sub Title</small></h1>`
- 2단계 제목
  - `<h2>Title</h2>`
  - `<h2>Title <small>Sub Title</small></h2>`
- 3단계 제목
  - `<h3>Title</h3>`
  - `<h3>Title <small>Sub Title</small></h3>`

```html
<h1>게시판 <small>목록보기</small></h1>
```

1단계 제목에는 아이콘을 삽입할 수 있다.

- `<h1 class="main">Title</h1>` : 메인 페이지
- `<h1 class="sub">Title</h1>` : 서브 페이지
- `<h1 class="page">Title</h1>` : 일반 페이지

```html
<h1 class="main">Spring Boot <small>Security</small></h1>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/d0aa13de-a3d2-49d4-b578-f9bd08bd31d8" />
<br><br>



### Form Controls

컨트롤의 모양을 지정한다.

크기(너비)를 지정할 수 있다. 대상: `<input>`, `<select>`, `<button>`, `<textarea>`

- `<input>` : width(User Agent)
- `<input class="short">` : width(100px)
- `<input class="long">` : width(350px)
- `<input class="full">` : width(100%)

```html
<input type="text" name="name" class="short" placeholder="이름 입력" />
<input type="text" name="tel" class="long" placeholder="연락처 입력" />
<input type="text" name="tel" class="full" placeholder="주소 입력" />
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/2f7333c3-0a33-4767-a4f6-d494e77969e8" />
<br><br>



### 버튼

메인 버튼에 색상을 지정할 수 있다.

- `<input type="button">`
- `<input type="submit">`
- `<button>`

```html
<input type="button" class="primary" />
```


### 이미지 버튼

`<button></button>` 태그에 이미지를 지정할 수 있다.

- `<button class="in">회원가입</button>`
- `<button class="out">회원탈퇴</button>`
- `<button class="login">로그인</button>`
- `<button class="logout">로그아웃</button>`
- `<button class="add">쓰기</button>`
- `<button class="back">돌아가기</button>`
- `<button class="list">목록보기</button>`
- `<button class="del">삭제하기</button>`
- `<button class="edit">수정하기</button>`
- `<button class="reply">답변하기</button>`
- `<button class="comment">댓글달기</button>`
- `<button class="home">홈</button>`
- `<button class="search">검색</button>`
- `<button class="menu">메뉴</button>`
- `<button class="close">닫기</button>`
- `<button class="settings">설정</button>`
- `<button class="favorite">즐겨찾기</button>`
- `<button class="star">스타</button>`
- `<button class="more">더보기</button>`
- `<button class="checkbox">체크박스</button>`
- `<button class="dialog">모달</button>`
- `<button class="calendar">달력</button>`
- `<button class="timer">타이머</button>`
- `<button class="map">지도</button>`
- `<button class="marker">마커</button>`
- `<button class="bookmark">북마크</button>`
- `<button class="tag">태그</button>`
- `<button class="image">이미지</button>`
- `<button class="folder">폴더</button>`
- `<button class="desc">파일</button>`
- `<button class="attach">첨부파일</button>`
- `<button class="copy">복사</button>`
- `<button class="paste">붙여넣기</button>`
- `<button class="click">클릭</button>`
- `<button class="keyboard">키보드</button>`
- `<button class="refresh">새로고침</button>`
- `<button class="pause">일시정지</button>`
- `<button class="secret">보안</button>`
- `<button class="person">유저</button>`
- `<button class="group">그룹</button>`
- `<button class="lock">잠금</button>`
- `<button class="language">언어</button>`
- `<button class="color">색상</button>`
- `<button class="left-panel">왼쪽 패널</button>`
- `<button class="right-panel">오른쪽 패널</button>`
- `<button class="json">JSON</button>`
- `<button class="markdown">마크다운</button>`
- `<button class="html">HTML</button>`
- `<button class="css">CSS</button>`
- `<button class="javascript">JavaScript</button>`


<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/109d2a8b-51d3-4594-8da1-01b44230d9c5" />
<br><br>



### Label Control

라벨이 있는 입력 도구를 만든다.(feat.텍스트박스)

```html
<div class="group">
  <label>아이디</label>
  <input type="text" />
</div>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/c30f134b-0277-4d40-a45a-abca35358a36" />
<br><br>



### Button Group

버튼 그룹을 만든다.(feat.input, button)

```html
<div class="group">
  <input type="button" value="확인" />
  <input type="button" value="취소" />
</div>

<div class="group">
  <button class="add">글쓰기</button>
  <button class="list">목록보기</button>
</div>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/127547e5-1af9-485f-89bd-8b029c0d214b" />
<br><br>



### Table

테이블 서식을 지정한다.

기본 설정

- 테두리(1px)
- 너비(100%) : `<table>`
- 너비(auto) : `<table class="content">`

```html
<table>
  <tr>
    <th>column</th>
    <th>column</th>
    <th>column</th>
  </tr>
  <tr>
    <td>cell</td>
    <td>cell</td>
    <td>cell</td>
  </tr>
  <tr>
    <td>cell</td>
    <td>cell</td>
    <td>cell</td>
  </tr>
</table>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/9cb39436-a1d3-40bd-8a85-746cf54cface" />
<br><br>


- 세로 모드 : `<table class="vertical">`

```html
<table class="vertical">
  <tr>
    <th>column</th>
    <td>cell</td>
  </tr>
  <tr>
    <th>column</th>
    <td>cell</td>
  </tr>
  <tr>
    <th>column</th>
    <td>cell</td>
  </tr>
</table>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/0dd3169a-ba9e-45cc-b9b3-ed799c9908f2" />
<br><br>

- 셀 수평 정렬
  - `<td>`: 중앙 정렬
  - `<td class="left">`: 좌측 정렬
  - `<td class="right">`: 우측 정렬

### Message

메시지를 표시한다.

```html
<div class="message long" title="Subject">Content</div>
```

너비를 지정한다.

- `<div class="message">Content</div>`: 100%
- `<div class="message short">Content</div>`: 250px
- `<div class="message long">Content</div>`: 500px

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/8b95ff1f-1c60-4612-8634-19b5b03842d0" />
<br><br>



### Badge

배지를 표시한다.

```html
<span class="badge right red">5</span>
```

방향(좌/우) 지정

- `<span class="badge left">5</span>`
- `<span class="badge right">5</span>`

색상 지정

- `<span class="badge red">5</span>`
- `<span class="badge yellow">5</span>`
- `<span class="badge blue">5</span>`
- `<span class="badge green">5</span>`
- `<span class="badge orange">5</span>`

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/40dd141f-b0ad-4560-bf70-cc5e2e6fcf08" />
<br><br>

### Seperate

컨테이너의 두 요소를 좌우로 분리 정렬한다.

```html
<div class="seperate">
  <div>자바</div>
  <div>오라클</div>
</div>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/9f503ce6-fa05-4703-889e-bf185cb78dc2" />
<br><br>


### HR

수평선을 만든다.

- `<hr>`: margin(1rem)
- `<hr class="thin">`: margin(0.5rem)
- `<hr class="thick">`: margin(2rem)

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/b1eb92bf-4f73-4a4c-b870-e7c0ceb19448" />
<br><br>


### List

목록을 만든다.

```html
<div class="box-list">
  <div>item</div>
  <div>item</div>
  <div>item</div>
</div>

<div class="box-list full">
  <div>item</div>
  <div>item</div>
  <div>item</div>
</div>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/e1c17378-7da9-476b-bf6f-88122373110f" />
<br><br>


### Flex

플랙스 레이아웃을 만든다.

```
- `<div class="flex">`: flex + item-align(center) + gap(5px)
- `<div class="flex gap픽셀">`: 0px ~ 20px
- `<div class="flex gap0">`: flex + item-align(center) + gap(0px)
- `<div class="flex gap1">`: flex + item-align(center) + gap(1px)
- `<div class="flex gap5">`: flex + item-align(center) + gap(5px)
- `<div class="flex gap10">`: flex + item-align(center) + gap(10px)
```

### Space

빈 `<div>`를 만든다. (세로 여백 띄우기용)

```
- `<div class="space">`: height(10px)
- `<div class="space픽셀">`: 1px ~ 20px
- `<div class="space1">`: height(1px)
- `<div class="space5">`: height(5px)
- `<div class="space10">`: height(10px)
```

### Programming Code

코드를 삽입한다.

```html
<pre class="code">
    int a = 10;
    System.out.println(a);
</pre>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/520bf334-d34b-45b8-b39d-278e4e9b7330" />
<br><br>


### Pagebar

페이지 바를 만든다.

- `<a href="#!" class="page now">5</a>`: 현재 페이지
- `<a href="#!" class="prev">&lt;&lt;</a>`: 이전(블럭) 페이지
- `<a href="#!" class="next">&gt;&gt;</a>`: 다음(블럭) 페이지

```html
<div class="pagebar">
  <a href="#!" class="prev">&lt;&lt;</a>
  <a href="#!" class="page">1</a>
  <a href="#!" class="page">2</a>
  <a href="#!" class="page">3</a>
  <a href="#!" class="page">4</a>
  <a href="#!" class="page now">5</a>
  <a href="#!" class="page">6</a>
  <a href="#!" class="page">7</a>
  <a href="#!" class="page">8</a>
  <a href="#!" class="page">9</a>
  <a href="#!" class="page">10</a>
  <a href="#!" class="next">&gt;&gt;</a>
</div>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/933d0cb5-9d80-4ac4-a35b-0b336c79e0ad" />
<br><br>


### Modal

모달을 띄운다. `group` 식별자를 통해 모달을 구성한다.

- `data-modal-button="group"` : 모달 트리거
- `data-modal-window="group"` : 모달
- `data-modal-title="title"` : 모달 제목
- `data-modal-ok="group"` : 확인 버튼
- `data-modal-cancel="group"` : 취소 버튼

```html
<div>
    <button class="modal" data-modal-button="add">글쓰기</button>
</div>

<div data-modal-window="add" data-modal-title="회원가입"">
    <div class="group">
        <label>이름</label>
        <input type="text" class="short">
    </div>
    <div class="group">
        <label>주소</label>
        <input type="text" class="full">
    </div>
    <div class="group">
        <label>전화</label>
        <input type="text" class="long">
    </div>
    <div>
        <button class="ok" data-modal-ok="add">확인</button>
        <button class="cancel" data-modal-cancel="add">닫기</button>
    </div>
</div>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/3274fd5e-12c8-4ce7-a32e-a061ce1b63b4" />
<br><br>


### Sidebar

사이드바를 띄운다. `group` 식별자를 통해 패널을 구성한다.

- `data-sidebar-button="group"` : 사이드바 트리거
- `data-sidebar-window="group"` : 사이드바
- `data-sidebar-title="Lorem ipsum"` : 사이드바 제목
- `data-sidebar-direction="right"` : 사이드바 방향(생략하면 left)
- `data-sidebar-size="wide"` : 사이드바 사이즈(생략하면 300px, wide 500px)

```html
<div>
  <button class="sidebar" data-sidebar-button="sidebar">사이드바 열기</button>
</div>

<div data-sidebar-window="sidebar" data-sidebar-title="Lorem ipsum">
  Lorem ipsum dolor sit amet consectetur adipisicing elit.
</div>
```

<img width="800" style="border: 1px solid #777; padding: 1px;" alt="Image" src="https://github.com/user-attachments/assets/3dae5bee-7c9b-4136-b8bf-a8efbf7ee52e" />
<br><br>

---

created by in. 2023.06

modified by in. 2025.05
