# 웹/XML 프로그래밍

웹/XML 프로그래밍 과목의 수업 예제, 개인 실습, 미니프로젝트와 결과 화면을 모은 학습 저장소입니다. 현재 자료는 **HTML·CSS·JavaScript를 이용한 웹 페이지 제작**을 중심으로 구성되어 있습니다.

## 주요 자료 바로가기

| 구분                 | 위치 및 내용                                                                                                    |
|----------------------|-----------------------------------------------------------------------------------------------------------------|
| 수업 예제            | [HTML5](HTML5/): 1~12장 예제와 장별 안내 페이지                                                                 |
| 개인 실습            | [practice](practice/): 장별 실습, 미니프로젝트, 결과 이미지                                                     |
| 캠퍼스 생활 안내     | [practice/Web_01](practice/Web_01/): HTML·CSS 페이지와 SVG 이미지                                               |
| 여행 후기 페이지     | [차민규_24117000.html](HTML5/chap_02/project/차민규_24117000.html): 여행 사진·후기, 이동 링크, 설문 및 CSS 효과 |
| 고양이 소개 프로젝트 | [3장 프로젝트](HTML5/chap_03/project/): 소개 페이지와 iframe 구성                                               |
| 라면 소개 프로젝트   | [4장 프로젝트](HTML5/chap_04/project/): 음식 소개 페이지와 CSS                                                  |

GitHub에서 HTML 파일 링크를 누르면 소스가 표시됩니다. 페이지의 화면과 동작은 저장소를 내려받아 브라우저에서 확인합니다.

## 디렉터리 구성

```text
web_xml_programming/
├── HTML5/                    # 수업 자료 및 장별 프로젝트
│   ├── chap_01/ ~ chap_12/   # 장별 예제와 안내 HTML
│   ├── font/                # 글꼴 관련 이미지 자료
│   ├── media/               # 이미지 자료
│   └── xmlprogramming/      # Java 초기 프로젝트
├── practice/                # 개인 실습과 결과 화면
│   ├── chap01/ ~ chap05/    # 장별 실습
│   └── Web_01/              # 캠퍼스 생활 안내 페이지
├── xmlprogramming/          # Java 초기 프로젝트
├── css/                     # 공통 스타일
├── font/                    # 글꼴 관련 이미지 자료
├── media/                   # 이미지 자료
├── img/                     # 이미지용 자리표시 폴더
├── js/                      # Webpack 진입 파일 및 vendor 폴더
├── index.html               # 수업 목차 페이지
├── image.js                 # 이미지 표시 스크립트
├── snow.js                  # 눈 내리기 효과 스크립트
├── styles.css               # 목차 페이지 스타일
├── style_xmp.css            # 예제 표시 스타일
├── package.json             # npm 실행 명령과 개발 의존성
├── webpack.*.js             # 공통·개발·배포 설정
└── README.md                # 저장소 전체 안내
```

루트에는 `404.html`, 아이콘, `robots.txt`, `site.webmanifest` 등의 웹 기본 파일과 편집기 설정도 있습니다. `node_modules/`는 로컬 의존성 폴더이며
`.gitignore`에 등록되어 있습니다.

## 장별 수업 자료

| 장 | 학습 내용                     | 안내 페이지                                  |
|----|-------------------------------|----------------------------------------------|
| 1  | HTML5와 웹 프로그래밍         | [index_01.html](HTML5/chap_01/index_01.html) |
| 2  | HTML5로 기본 문서 만들기      | [index_02.html](HTML5/chap_02/index_02.html) |
| 3  | 문서 구조화와 웹 폼           | [index_03.html](HTML5/chap_03/index_03.html) |
| 4  | CSS3로 웹 페이지 꾸미기       | [index_04.html](HTML5/chap_04/index_04.html) |
| 5  | CSS3의 고급 기능              | [index_05.html](HTML5/chap_05/index_05.html) |
| 6  | 자바스크립트와 ES6            | [index_06.html](HTML5/chap_06/index_06.html) |
| 7  | 자바스크립트 객체 다루기      | [index_07.html](HTML5/chap_07/index_07.html) |
| 8  | 문서 객체모델 이해하기        | [index_08.html](HTML5/chap_08/index_08.html) |
| 9  | 이벤트 처리하기               | [index_09.html](HTML5/chap_09/index_09.html) |
| 10 | 브라우저 객체모델과 반응형 웹 | [index_10.html](HTML5/chap_10/index_10.html) |
| 11 | 캔버스로 그림 그리기          | [index_11.html](HTML5/chap_11/index_11.html) |
| 12 | 도전! 프로젝트                | [index_12.html](HTML5/chap_12/index_12.html) |

장별 폴더의 `html/`에는 개별 예제, `media/`에는 관련 이미지·미디어, `project/`에는 프로젝트 자료가 들어 있습니다. 이 하위 폴더 구성은 장마다 다릅니다. 1장은 `HTML/`, `CSS/`,
`jscript/`로 구분하며, 4장에는 `review/`, 12장에는 `horse/`, `rainbow/`, `slot/` 프로젝트 폴더가 있습니다.

## 개인 실습 및 프로젝트

| 위치                                | 주요 내용                                                      |
|-------------------------------------|----------------------------------------------------------------|
| [practice/chap01](practice/chap01/) | 자기소개 과제, 기초 HTML 실습과 결과 화면                      |
| [practice/chap02](practice/chap02/) | 목록·시간표 실습, 햄버거 소개 미니프로젝트와 이미지            |
| [practice/chap03](practice/chap03/) | 문서 구조, iframe, 입력 폼 실습 및 미니프로젝트 자료           |
| [practice/chap04](practice/chap04/) | 스타일 적용 순서·선택자 실습, CSS 속성별 예제·캡처 및 제출 ZIP |
| [practice/chap05](practice/chap05/) | 글자 크기 전환·커서 실습, 변환·전환·애니메이션 학습 화면 캡처  |
| [practice/Web_01](practice/Web_01/) | 캠퍼스 생활 안내 페이지 2개, 스타일, SVG 이미지와 결과 화면    |

- `practice/chap05/prac01.html`: 글자 위에 마우스를 올리면 5초 동안 글자 크기가 500%까지 커지는 전환 효과입니다.
- `practice/chap05/prac02.html`: `crosshair`, `help`, `pointer`, `progress`, `n-resize` 커서를 비교합니다.
- 여행 후기 페이지는 5장 CSS 학습과 관련되어 있지만 실제 파일은 `HTML5/chap_02/project/차민규_24117000.html`에 있습니다. 같은 폴더의 `24117000.css`와
  `HTML5/chap_05/media/`의 사진을 사용합니다.
- `HTML5/chap_05/project/`에는 제공된 `홍길동_20230808.html` 템플릿과 `20230808.css`가 있습니다.
- `HTML5/chap_03/project/`, `HTML5/chap_04/project/`에는 HTML·CSS 원본과 제출용 ZIP 파일이 함께 있습니다.
- `HTML5/chap_06/project/`에는 날짜·시간 표시와 색상 변경 예제가 있습니다.

## 실행 방법

### 브라우저에서 HTML 열기

1. 저장소를 내려받거나 복제합니다.
2. 위 장별 안내 페이지 또는 원하는 실습 HTML 파일을 브라우저로 엽니다.
3. 이미지, CSS, 스크립트와 iframe이 상대 경로를 사용하므로 폴더 구성을 유지합니다.

현재 루트 `index.html`의 장별 링크는 `chap_01/` 등의 경로를 가리키지만 실제 장별 자료는 `HTML5/chap_01/` 등에 있습니다. 위 표의 실제 경로로 접근하면 원하는 안내 파일을 찾을 수
있습니다.

### npm 개발 서버 및 빌드

Node.js와 npm을 사용할 수 있는 환경에서 저장소 루트에서 실행합니다.

```sh
npm ci
npm start
```

`npm start`는 Webpack 개발 서버를 실행하고 브라우저를 엽니다. 개발 서버의 정적 파일 제공 위치는 저장소 루트입니다.

```sh
npm run build
```

배포 빌드 결과는 `dist/`에 생성됩니다. 현재 설정은 루트 `index.html`과 지정된 기본 정적 파일을 대상으로 하며, `HTML5/`, `practice/`, 루트 `media/`·`font/` 전체를
복사하지 않습니다. 전체 수업 자료를 웹에 배포하려면 배포 대상과 경로를 추가로 구성해야 합니다.

`js/app.js`는 현재 비어 있습니다. `npm test`는 테스트가 구성되지 않았다는 메시지와 함께 종료하는 기본 명령입니다.

### Java 초기 프로젝트

`xmlprogramming/`과 `HTML5/xmlprogramming/`에는 각각 `src/App.java`가 있으며, 현재 구현은 `Hello, World!` 출력입니다. 두 폴더는 별도의 초기 프로젝트로
확인할 수 있습니다.

- [xmlprogramming 안내](xmlprogramming/README.md)
- [HTML5/xmlprogramming 안내](HTML5/xmlprogramming/README.md)

## 자료 및 사용 참고

실습 화면 캡처와 제출 ZIP은 학습·과제 기록으로 보관합니다. 수업 예제, 외부 학습 사이트 자료, 이미지 등을 재사용할 때는 각 자료의 출처와 이용 조건을 확인해 주세요.
루트 [LICENSE.txt](LICENSE.txt)에는 HTML5 Boilerplate 라이선스 고지가 있습니다.
