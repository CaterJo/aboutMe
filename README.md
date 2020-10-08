# About Me

    안녕하세요 프론트엔드 개발자 조병규입니다.
    사용자에게 직관적인 서비스, 동료에게 가독성이 좋은 코드를 제공하는 것을 중요하게 생각합니다.
    웹을 통해 사회의 편리함을 제공하는 일에 관심이 있습니다.
    유연한 근무환경과 오픈 커뮤니케이션을 지향하며
    React와 Typescript 그리고 작업물을 문서화하는 것을 좋아합니다.

- 이름: 조병규
- 나이: 30살 (1991년생)
- 학력: 대졸 (한국교통대학교, 기계공학)
- 병역: 육군 만기제대(11.09 ~ 13.06)
- 거주지: 서울 동작구
- e-mail: byeonggyu303@gmail.com
- Skill
  - front: React(+Redux), Typescript, ES6+, Scss
  - back: Node.js, Mysql, MongoDB
  - etc: Git, Webpack, Babel, Jenkins

## Career

### [인스웨이브시스템즈](https://www.inswave.com/websquare/websquare.html?w2xPath=/index.xml)

- 소개: 웹표준 UI솔루션 기업
- 기간: 2018.03~2020.05
- 부서: 솔루션사업팀
- 소개: JavaScript 기반의 web framework, Websquare 솔루션 기업.
- 역할
  1. 마이그레이션 솔루션 기능개선 및 관리([w-craft](https://www.inswave.com/websquare/websquare.html?w2xPath=/websquare5/craft.xml&product=ws&seq=19))
  2. 워크플로우 솔루션 기능개선 및 관리.([x-Touch](https://www.inswave.com/websquare/websquare.html?w2xPath=/websquare5/xtouch.xml&product=ws&seq=56))
  3. 신규 구축 프로젝트 투입.

---

## Projects

### 1.광주은행 모바일 웹

- 기간: 2018.06~2018.12
- 소개: REST API를 이용한 모바일 웹뱅킹 구축.
- 사용기술: Websquare, javascript, Spring
- 세부내용: [클릭](./project/광주은행.md)
- 뉴스: [광주은행 모바일웹뱅킹 구축](https://www.zdnet.co.kr/view/?no=20181107210051)
- 참고: [광주은행 모바일웹](https://m.kjbank.com/mbdt/)
- 작업내용
  - 금융상품 3종 (KJB 주거래통장, Y통장, 멀티통화외화예금)
  - 서비스 5종 (이체한도변경, 장기미사용해제, 광주은행 지점찾기, 번호표뽑기, 입출금 알림서비스)
  - 다음 map API를 이용한 은행지점 찾기 서비스

### 2.마이그레이션 솔루션 플렛폼 추가 개발

- 기간: 2019.03~2019.05
- 소개: 소프트베이스 사의 [xframe](http://www.xframe.co.kr/)을 인스웨이브의 websquare 파일로 전환하는 로직 구현
- 사용기술: node.js, mongoDB, express, ES6
- 세부내용: [클릭](./project/wcfraft.md)
- 작업내용:
  - xFrame 대한 전환룰(컴포넌트, script)을 작성
  - 기존 전환툴에 전환을 위한 Core 로직은 작성된 상황이라 큰 어려움은 없었음.

### 3.롯데손해보험 채권앱 어드민 개발

- 기간: 2019.05~2019.06
- 소개: 수행사에서 사용하는 template 프로젝트를 기반으로 어드민 개발
- 사용기술: OracleDB, spring, websquare
- 상세보기: [클릭](./project/admin.md)
- 작업내용:
  - WRM(WebSquare5 Reference Model, 웹스퀘어 프로젝트 표준 모델)을 기반으로 관리자 프로젝트 개발.
  - 구글OTP를 이용한 인증 처리

### 4.KB증권 디지털 자산관리 플랫폼

- 기간: 2019.07~2020.01
- 소개: workFlow 솔루션의 기술지원 및 안정화
- 참고: [xTouch](https://www.inswave.com/websquare/websquare.html?w2xPath=/websquare5/xtouch.xml&product=ws&seq=56)
- 세부내용: [클릭](./project/workflow.md)
- 작업내용:
  - 워크플로우 솔루션(xTouch) 커스터마이징 및 기능개선.
  - 상품가입 이어가기
  - 화면 뒤로가기

---

## Toy Project

### 1.미세먼지 조회

- 소개: 네이버 map과 공공 API를 이용한 실시간 미세먼지 조회.
- 참고: [repository](https://github.com/CaterJo/misemise)
- 사용기술: React, express, gulp
- 작업내용
  - 공공 API연동
  - geoJSON을 네이버 map에 레이어로 덫씌우는 작업.
  - node.js 크롤링을 이용해 geoJSON파일이 업데이트됐을 때 소스파일을 자동 업데이트.
  - 배포 프로세스 구축(jenkins, heroku, github)연동.

### 2.Memo

- 소개: TypeScript와 Redux연동을 연습하기 위한 간단한 메모앱.
- 참고: [repository](https://github.com/CaterJo/memoApp)
- 사용기술: React(+Redux), Typescript
- 작업내용:
  - redux에 정적타입을 어떻게 적용할 것인가에 대한 가이드라인 구축.
  - [redux with typescript](https://github.com/CaterJo/TIL/blob/master/react/typescript.md)

### 3.Blog

- 소개: 리액트를 이용한 블로그.
- 참고: [repository](https://github.com/CaterJo/blog-front)
- 기간: 2020.01~2020.05
- 사용기술: React, Typescript, express, mongoDB, Styled Component
- 작업내용:
  - **Styled component**와 css 프레임워크인 sementic-UI을 이용한 디자인
  - hooks 기반 함수형 컴포넌트로 상태관리
  - Redux + Typescript
  - **redux-saga**를 이용한 컴포넌트 사이드이펙트 관리.
  - **JWT**을 이용한 인증처리
  - [리액트를 다루는기술](https://book.naver.com/bookdb/book_detail.nhn?bid=15372757)에 소개된 소스코드를 기반으로 기능추가 및 수정

---

## Skill

### Overall

- 클린코드를 지향합니다.
- 서비스 품질개선을 위해서 적극적으로 학습합니다.
- 최신 기술은 시장 관심도에 발 맞추어 학습하며 도입효과와 비용에 대해서 고민합니다.
- 시장과 소비자와의 커뮤니케이션을 중요하게 생각합니다.

### Communication

- 항상 조율이 가능한 오픈된 커뮤니케이션을 지향합니다.
- 상대방의 언어로 말하며 디자이너와 기획자와 원활한 커뮤니케이션을 할 수 있도록 노력합니다.
- 신기술을 좋아하지만 생산성과 효용성을 감안하며 기술자로써의 아집을 버리기위해 노력합니다.

### HTML/CSS

- **Semantic Web**을 지향합니다.
- BEM등의 class 명명 규칙을 준수합니다.
- 반응형 웹을 구현할 수 있습니다.
- 미디어 쿼리를 이용한 멀티 브라우징을 구현할 수 있습니다.
- CSS 프레임워크는 bootstrap과 **Material-UI**를 사용해 봤습니다.

### Javascript

- ES6 이후의 문법에 익숙합니다.
- prototype기반 OOP를 충분히 이해하고 있습니다.
- 라이브러리없이 DOM을 조작하는데 능숙합니다.
- 비동기 작업을 하는데 익숙합니다. (promise, async await)

### Typescript

- 상황에 맞는 정적 type체크를 탄력적으로 적용할 수 있습니다.
- 초기 기술 도입시 고려사항 인지하고 있으며 상황에 적절하게 사용하기 위해 노력합니다.

### React

- 렌더링과 재사용성을 기준으로 컴포넌트를 분리합니다.
- **Hooks**를 능숙하게 사용합니다.
- **Redux**를 이용한 전역 상태관리와 관련 미들웨어 사용에 익숙합니다.
  - (redux-saga, redux-thunk, connected-react-router)
- 컴포넌트 라이프사이클을 이해하고 상황에 맞게 사용할 수 있습니다.
- 상태관리 라이브러리를 이용할 때, 서버에서 관리할 데이터와 클라이언트에서 관리할 데이터를 구분합니다.

### Server

- **Express**에서 REST API를 작성할 수 있습니다.
- JWT 인증을 사용하여 브라우저 쿠키에 저장하고 세션 처리를 할 수 있습니다
- Express를 활용하여 **RESTful API**를 작성할 수 있습니다.

### Tools

- Webpack (+Babel)
- Jira
- Slack
- Confluence
- Notion
- VS Code

---

## FAQ

### 1.비전공 개발자로써 개발을 하기로 한 이유가 있다면?

학부생시절 전공수업으로 배웠던 프로그래밍이 즐거웠습니다.  
기계공학을 전공했는데 기계공학은 제가 생각했던것 보다 굉장히 막연하고 거시적인 학문 이었습니다.  
열역학, 유체역학, 동역학같은 전공수업은 점점 제 이해수준을 벗어나 뜬 구름 잡는 소리처럼 느껴졌고 진로에 대해 많은 고민을 했습니다.  
그러다가 전공과목으로 프로그래밍 수업이 듣게 됐고 이 수업이 제가 개발자가 된 계기가 되었습니다.  
한 학기동안 수강하며 기말고사로 간단한 게임을 만드는 수업이었는데 기획을 구체화시키고 기능을 추가하는 과정이 참 재밌었습니다.
이 수업을 들으며 개발자가 되는것을 꿈꿨고 6개월의 웹 개발자 국비교육과정과 4개월의 사설 개발자 학원과정을 거쳐 아이티 회사에 취업을 했습니다.

### 2.개발자로서의 본인의 비전을 이야기 해달라

저는 시장과 능동적이고 꾸준하게 소통하는 개발자입니다.  
시장에서 관심이 받는 기술이 있으면 찾아서 공부해보고 간단한 코드를 작성해보며 감을 익힌뒤,
자세한 내용은 포스팅을 합니다.  
이 작업만이 제가 기술이 익혔다는 것을 느끼게 합니다.  
항상 시장의 흐름에 맞춰나기위해 노력합니다.  
물론 모든것 다룰 수 없기 때문에 우선순위를 가장 중요하게 생각합니다.  
가장 큰 우선순위는 시장의 관심도와 기술의 필요성에 대한 공감입니다.

### 3.개발자가 되기 위해서 어떻게 공부하였는가

새로운 기술을 학습할 때는 튜토리얼을 따라해보고 간단한 repository를 만들어서 실습해봅니다.  
실습을 하면서 중간중간에 만나는 문제는 개인 [Repository](https://github.com/CaterJo/TIL)에 포스팅을 합니다.

### 4.프론트엔드 개발자는 어떤 역할을 한다고 생각하나? 프론트 엔드를 하고싶은 이유는?

제 관심은 제가 기업에 제공하는 서비스를 이용하는 사람들의 만족감을 높히는 것입니다.  
이를 위해 가장 사용자와 가까운 곳에 있는 포지션이 프론트엔드라고 생각합니다.  
직관적인 서비스와 유연한 인터페이스를 제공하는 것과 웹 서비스를 이용하면서 느끼는 작은 불편함들은 개선하는데 관심이 있습니다.

### 5.회사 기술 스택에 맞추어 단기간 내에 언어와 프레임워크를 학습 하여야 할 때, 어떻게 공부하고 해결할 것인가?

가장 빠르게 학습할 수 있는 방법은 동영상을 보며 실습을 하는 것입니다.  
수백 페이지의 아이티 책을 끝까지 학습하는 것은 상당히 어려운 일입니다. 새로운 프레임워크나 언어를 학습할 때 입문용 동영상을 학습하고 지식의 전반적인 내용을 습득한 뒤 더 깊은 지식이 필요한 시점에 책을 보면 좋습니다.  
이 때 원하는 부분만 목차에 찾아서 보는식으로 학습니다. 그 밖에 아직 컨텐츠로 나오지 않은 지식들은 해외 블로그나 공식 document를 참고합니다.  
그리고 이렇게 해서 알게된 지식들을 포스팅을 해둡니다. 이 포스팅들은 저만의 Wiki가 되고 학습했던 내용을 리마인드할 수 있고 더 깊이 있는 지식을 학습 할 때 저의 이해수준의 기준이 됩니다.

### 6.비전공자 개발자로서 콤플렉스나 어려움은 없나?

처음 개발자가 되어야겠다고 생각했을 때는 큰 콤플렉스였습니다.  
현재는 그런 생각을 완벽히 떨쳐버렸습니다. 그 보다 중요한 것이 지속적인 학습과 개발경험이라고 생각합니다.  
물론 학습을 하다보면 배경지식이 필요한 순간이 있습니다.  
저는 그런 순간에 Top Down방식으로 해당 기술을 익히기 위한 배경지식을 부분적으로 학습합니다.  
이렇게 해야 광범위한 아이티지식에서 학습의 우선순위를 정할 수 있습니다.  
예를 들어 React를 학습하기 위해서는 ES6의 `class`, `arrow function`, `module`, `promise`등의 문법을 숙지해야합니다.  
이런 문법적 허들이 생겼을 때마다 배경지식을 하나씩 추가하면 됩니다.  
React를 하기 위해서 javascipt의 모든 명세를 암기할 필요는 없습니다.

컴퓨터공학에서 다루는 전공지식도 같은식으로 접근합니다.  
어떤 배경지식으로 인한 허들이 생겼을 때, 새로운 지식을 받아들이기 위한 지식을 정리합니다.

### 7.React를 모르는 사람에게 React를 선택해야하는 이유를 설명한다면?

우선 제가 React를 학습한 이유는 모바일웹의 성장에 따른 인터렉티브한 웹의 수요가 증가할 것이라 판단했기 때문입니다.  
그 중 제가 학습할당시 가장 인지도가 높은 라이브러리인 React를 선택해서 학습했습니다.

React는 간단히 소개하자면 인터렉티브한 웹과 앱을 만들기 위한 라이브러리라고 할 수 있습니다.  
가상돔을 이용한 랜더링 최적화와 컴포넌트 단위로 화면을 설계할 수 있어 동적인 웹을 만드는데 포커스가 맞춰져 있습니다.

리액트를 선택하는 강점을 꼽자면

1. 아이티 대기업에서 관리
2. 방대한 커뮤니티
3. 국내 기술 수요 1위
4. template문법없이 javascript만 잘 알면 접근 가능.
5. Reactive Naitive를 이용한 앱개발 가능

정도라고 생각합니다.

### 8.Typescript를 사용함으로써 얻을 수 있는 장점은?

제가 타입스크립트를 선택한 이유는 타입체크와 추가적인 언어기능을 통해 좀더 프로그래밍이 가능하기 때문에 학습했습니다.  
우선 정적타입 도구를 선택하기로 했다면 선택지중 Typescript가 갖는 장점은 javascript의 상위호완이라는 점이라고 생각합니다.  
친숙하면서 선택적으로 기능을 도입할 수 있기때문에 도입 초반에 급격한 러닝커브를 겪지 않아도 됩니다.

1. 정적타입
   - 컴파일 단계에서 오류를 포착할 수 있음.
2. 강력한 객체지향 프로그래밍
   - interface, Generic등 java에 익숙한 기능을 지원.
3. IDE 호환에 따른 생산성 향상.
   - 코드 어시스트
   - 타입 체크
4. 자바스크립트의 호환성
   - 자바스크립트의 상위호환이기 때문에 단계적 학습과 적용이 가능하다.
   - 자바스크립트 개발자가 학습하기 수월함
   - 문법이 자바스크립트와 굉장히 유사함.
