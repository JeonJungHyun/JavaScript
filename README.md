# JavaScript Study

HTML, CSS, Tailwind CSS, JavaScript DOM 조작을 단계별로 연습하는 학습용 예제 모음입니다.

브라우저에서 HTML 파일을 직접 열어 실행할 수 있으며, 별도의 빌드 도구나 패키지 설치가 필요하지 않습니다.

## 프로젝트 구성

```text
.
├── ex01.html
├── ex02css.html
├── ex03css.html
├── ex04tailwind.html
└── js_study01/
    ├── ex01.html
    ├── ex02css.html
    ├── ex03css.html
    ├── ex04tailwind.html
    ├── js_ex01.html
    ├── js_ex02.html
    ├── js_ex03.html
    ├── js_ex04.html
    ├── js_ex05.html
    ├── js_ex06.html
    ├── js_ex07.html
    ├── js_ex08.html
    ├── js_todolist.html
    └── js_study01/
        └── js_ex01.html ~ js_ex08.html
```

## 예제 설명

### HTML/CSS 기본 예제

| 파일 | 내용 |
| --- | --- |
| `ex01.html` | 기본 HTML 구조, 문단, 표, 링크, 목록 작성 연습 |
| `ex02css.html` | 내부 CSS 작성, 태그 선택자와 클래스 선택자 연습 |
| `ex03css.html` | 메뉴 형태의 `ul/li` 스타일링, `float`, `hover` 효과 연습 |
| `ex04tailwind.html` | CDN 방식으로 Tailwind CSS를 불러와 유틸리티 클래스 사용 |

루트의 `ex01.html` ~ `ex04tailwind.html` 파일은 `js_study01/` 안의 같은 이름 파일과 동일한 내용입니다.

### JavaScript 예제

| 파일 | 학습 주제 |
| --- | --- |
| `js_study01/js_ex01.html` | `document.write`, `prompt`, `console`, `getElementsByClassName` |
| `js_study01/js_ex02.html` | `querySelector`, `querySelectorAll`, 스프레드 연산자 |
| `js_study01/js_ex03.html` | `window.onload`, 버튼 클릭 이벤트, `innerHTML`, 문서 제목/배경 변경 |
| `js_study01/js_ex04.html` | 입력값 읽기, 리스트에 할 일 추가, 입력창 초기화와 포커스 |
| `js_study01/js_ex05.html` | 배열 데이터 기반 Todo 목록 렌더링 |
| `js_study01/js_ex06.html` | 입력값을 배열에 추가하고 화면 다시 그리기 |
| `js_study01/js_ex07.html` | `data-*` 속성, `findIndex`, `splice`를 이용한 삭제 기능 |
| `js_study01/js_ex08.html` | Todo 완료/삭제 기능 확장 연습 |
| `js_study01/js_todolist.html` | Todo 추가, 완료 토글, 삭제, `localStorage` 저장 기능이 포함된 완성형 예제 |

`js_study01/js_study01/` 폴더에는 `js_ex01.html` ~ `js_ex08.html` 예제가 한 번 더 들어 있습니다. 대부분 같은 내용이며, `js_ex08.html`에는 일부 문자열 차이가 있습니다.

## 실행 방법

1. 이 폴더를 에디터에서 엽니다.
2. 원하는 `.html` 파일을 브라우저로 엽니다.
3. JavaScript 예제는 브라우저 개발자 도구의 Console 탭을 함께 확인하면 좋습니다.

예를 들어 완성형 Todo List는 아래 파일을 열면 됩니다.

```text
js_study01/js_todolist.html
```

## 학습 흐름 추천

1. `ex01.html`로 HTML 기본 태그를 확인합니다.
2. `ex02css.html`, `ex03css.html`로 CSS 선택자와 레이아웃을 연습합니다.
3. `ex04tailwind.html`로 Tailwind CSS 유틸리티 클래스를 확인합니다.
4. `js_ex01.html`부터 `js_ex08.html`까지 순서대로 DOM 선택, 이벤트, 배열 렌더링, 삭제 기능을 익힙니다.
5. 마지막으로 `js_todolist.html`에서 `localStorage`를 이용한 데이터 저장 흐름을 확인합니다.

## 참고 및 주의점

- 이 프로젝트는 정적 HTML 파일 모음이므로 `npm install`이나 서버 실행이 필요하지 않습니다.
- `ex04tailwind.html`은 Tailwind CSS CDN을 사용하므로 인터넷 연결이 필요합니다.
- `js_study01/js_ex06.html`에는 `todoInput.focus();s`처럼 오타로 보이는 코드가 있어 실행 시 오류가 발생할 수 있습니다.
- 일부 예제에는 의도적으로 미완성 과제 주석이 남아 있습니다. 단계별 학습을 위한 연습 코드로 보면 됩니다.
- `js_todolist.html`은 브라우저 `localStorage`에 `myTodoList`라는 키로 Todo 데이터를 저장합니다. 저장된 목록을 초기화하려면 개발자 도구에서 해당 키를 삭제하거나 브라우저 사이트 데이터를 지우면 됩니다.

