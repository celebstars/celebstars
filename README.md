<img width="959" alt="celebstars" src="https://user-images.githubusercontent.com/48630055/196873250-db67b066-8f9f-4a12-848c-0608dc2954b6.png">


# Celebstars
- [KDT - 1차 프로젝트](https://joodeng.notion.site/joodeng/Joo-Young-Lee-61db50959426458db50275c985d2de2a?p=a073b61b1cc744e1872f3cb248d82f82&pm=c)
- 20220815 ~ 20220829
- Use: HTML, CSS, JavaScript, Git, Node.js, Express

## 프로젝트 소개
### On Demand CASTING 서비스란?
**기업이 원하는 금액으로 원하는 모델, 배우를 실시간 캐스팅**
- 쉽고 간편하게 그리고 빠르게 !!
- 기업과 모델/배우들이 자유롭게 지원하고 모집할 수 있는 서비스 
- 모델/배우 캐스팅 전문 플랫폼


## 페이지 설계
<img width="937" alt="celebstars1" src="https://user-images.githubusercontent.com/48630055/196873605-bd1b7f50-837c-4cb7-b82f-5d80a7bcefbe.png">


- 전체적인 UI/UX, 메인 컬러 디자인
- 3개의 break point를 두어 반응형 페이지 구현
## 구현 기능
> ### 메인 페이지
- position fixed를 이용해 navbar 가시성 확보
- 부트스트랩을 이용한 배너, 캐러셀 CSS 변경
- hasClass, addClass, removeClass를 이용해 두 가지 영상 파일을 번갈아가며 재생하도록 설정
- scrollTo를 이용해 탑 스크롤 버튼 구현
> ### 회원가입 페이지
- 회원가입 시 유효성 검사 구현
- 카카오 우편번호 API 사용
> ### 캐스팅 페이지
- 카테고리 옵션 구현
- 북마크 구현
> ### 오픈 프로필 페이지
- 프로필 모음 캐러셀 구현
- 북마크 구현
- 카테고리 옵션 구현
> ### 프로필 상세보기 페이지
- 버튼( 또는 스크롤 )으로  화면 이동 가능
- 화면 맨 아래가 되면 화면 상단으로 이동할 수 있는 이벤트 생성
> ### 마이 프로필 페이지
- 프로필 캐러셀 구현
- 프로필 편집 페이지 구현
> ### 커뮤니티 페이지
- Table을 이용해 직접 게시판 형태 제작
- 페이지 버튼과 글쓰기 버튼 등 hover 적용 해 가시성 확보
> ### 고객 지원 페이지
- FAQ - W3Schools의 Accordion 제작 후 UI 적용
- FAQ - forEach를 사용해 각각의 Accordion이 따로 동작하게 설계
- 정보 & 팁 / 셀럽 제휴 할인 - Table을 이용해 직접 게시판 형태 제작
- 이벤트 - ejs 문법으로 for문을 돌려 진행 이벤트만큼 나열
- Q & A - 문의하기 버튼 클릭 시 Modal ****생성, 제출 시 Sweet Alert 사용
> ### 클라우드 서버 구축
- 네이버 클라우드 플랫폼을 이용해 웹 서버 구축
