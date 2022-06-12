# 💻 Project
* 제목 : HTML, CSS를 이용한 프론트엔드 개발 교육 프로그램 홍보 페이지 구현 프로젝트
* 기한 : 2022-06-11 ~ 2022-06-12
* 목적
  * HTML, CSS 학습
  * Bootstrap 그리드 시스템 작동 원리 및 사용법 이해
* 설명
  * Bootstrap 그리드 시스템을 이용하여 반응형으로 구현한 웹 페이지
  * IE, FF, 크로미움 기반 브라우저(CR, EG, WH, OP)에서 정상 출력 확인
* 데모 페이지 : https://sypear.github.io/frontend-web-dev-course-promo-page/

# 🔎 What I Learned
<b>1. Sectioning Elements 사용 시에는 반드시 Heading이 포함되어야 함</b><br/><br/>

<b>2. Usability 고려</b><br/>
* Heading은 스타일적인 요소가 아니라 구조와 관련된 요소이다.
  * Heading 순서에 따라 스크린 리더가 탐색 하는 방법이 결정된다.
  * 따라서 올바른 순서로 Heading을 사용해야 한다.
  * ex) h1, h2를 작성하지 않았는데 h3을 작성하는 케이스 or h1 작성 후 h2를 건너뛰고 h3을 작성하는 케이스 등 지양<br/><br/>
* 이미지가 정보 컨텐츠와 관련 없을 경우 HTML이 아닌 CSS로 삽입한다.<br/><br/>
* Placeholder보다 label을 사용하자.<br/>
  * 브라우저 번역 기능 사용 시 Placeholder는 번역되지 않는다.<br/>
  * 스크린 리더 사용 시 Placeholder의 내용을 읽지 않는다.<br/><br/>

<b>3. flex-grow와 flex-shirink 사용</b><br/>
* 반응형 웹을 구현하기 위해 사용하는 속성
  * 화면 크기가 줄어들거나 늘어날 때 요소들의 크기 변화를 상대적으로 지정하기 위하여 사용<br/><br/>
* flex-grow
  * <b>여유 공간이 있는 경우</b> 기본으로 형성되는 크기보다 더 커질 수 있는지를 결정
  * 'flex-grow'를 1 이상으로 선언하면 여유 공간이 있는 경우 여유 공간을 차지 (default값: 0)
  * 속성 값이 클수록 공간을 차지하는 비율도 커짐
  * 여유 공간이 없는 경우 역할을 하지 않음<br/><br/>
* flex-shirink
  * <b>공간이 축소되는 경우</b> 기본으로 형성되는 크기보다 더 작아질 수 있는지를 결정
  * 'flex-shirink'를 1 이상으로 선언하면 공간이 축소되는 경우에 요소의 크기도 축소됨 (default값: 1)
  * 속성 값이 클수록 축소되는 비율도 커짐
  * 여유 공간이 있는 경우 역할을 하지 않음
  * 공간이 축소되는 경우 요소의 너비가 줄어들지 않도록 하기 위해 'flex-shirink: 0' 속성 부여 가능

# 📝 License
* '김버그의 CSS는 재밌다' 강의 수강 후 복습을 위하여 진행한 프로젝트입니다.
* 디자인 시안의 저작권은 모두 김버그님께 있습니다.
