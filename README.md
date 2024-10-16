# nextjs_study

## Next.js 란?

Next.js는 풀스택 웹 애플리케이션을 빌드하기 위한 React 프레임워크이다. React Components를 사용하여 사용자 인터페이스를 빌드하고 Next.js를 사용하여 추가 기능과 최적화를 구현한다.<br/><br/>
후드 아래에서 Next.js는 번들링, 컴파일 등과 같이 React에 필요한 툴링을 추상화하고 자동으로 구성한다. 이를 통해 구성에 시간을 들이는 대신 애플리케이션 빌드에 집중할 수 있다.<br/><br/>
개인 개발자이든 대규모 팀에 속한 사람이든 Next.js는 대화형, 동적인, 빠른 React 애플리케이션을 구축하는 데 도움을 줄 수 있다.

<br/><br/>

## 주요 특징

Next.js의 주요 기능은 다음과 같다.
- 라우팅 : 레이아웃, 중첩 라우팅, 로딩 상태, 오류 처리 등을 지원하는 서버 구성 요소를 기반으로 구축된 파일 시스템 기반 라우터이다.
- 표현 : 클라이언트 및 서버 구성 요소를 사용한 클라이언트 측 및 서버 측 렌더링, Next.js를 사용한 서버에서 정적 및 동적 렌더링으로 더욱 최적화. Edge및 Node.js 런타임에서 스트리밍
- 데이터 패칭 : 서버 구성 요소에서 async/await를 사용하여 간소화된 데이터 가져오기와 fetch 요청 메모 생성, 데이터 캐싱 및 재검증을 위한 확장된 API가 제공된다.
- 스타일링 : CSS모듈, Tailwind CSS, CSS-in-JS 를 포함한 선호하는 스타일링 방법 지원
- 최적화 : 이미지, 글꼴, 스크립트를 최적화하여 애플리케이션의 Core Web Vitals와 사용자 경험을 개선
- TypeScript : 더 나은 유형 검사와 더 효율적인 컴파일, 그리고 사용자 저으이 TypeScript플러그인과 유형 검사기를 통해 TypeScript에 대한 지원이 개선됨

<br/><br/>

## 앱 라우터 대 페이지 라우터

Next.js에는 App Router와 Pages Router라는 두 가지 라우터가 있다. App Router는 React의 최신 기능(예 : Server Components 및 Streaming)을 사용할 수 있는 새로운 라우터이다. Page Router는 원래 Next.js 라우터로, 서버 렌더링 React 애플리케이션을 빌드할 수 있게 해주며 이전 Next.js 애플리케이션에서도 계속 지원된다.
