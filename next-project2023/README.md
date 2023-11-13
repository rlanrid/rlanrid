# Next를 이용한 포트폴리오 사이트만들기
Next.js는 React 기반의 웹 애플리케이션을 빌드하기 위한 JavaScript 프레임워크입니다. 이 프레임워크는 서버 사이드 렌더링 (SSR) 및 정적 사이트 생성 (Static Site Generation)과 같은 고급 기능을 지원하여 개발자가 더 나은 성능과 검색 엔진 최적화를 달성할 수 있도록 도와줍니다. 다음은 Next.js의 주요 특징과 개념에 대한 간략한 설명입니다.

1. 서버 사이드 렌더링 (SSR): Next.js는 페이지를 서버에서 사전에 렌더링하여 클라이언트에 보내므로 초기 로딩 속도가 향상되고 검색 엔진 최적화가 강화됩니다. 이는 사용자에게 빠르게 콘텐츠를 제공하는 데 도움이 됩니다.

2. 정적 사이트 생성 (SSG): Next.js는 페이지를 미리 빌드하여 정적인 HTML 파일을 생성할 수 있습니다. 이는 페이지를 렌더링할 때 서버에 부담을 주지 않고 정적 파일을 제공하여 빠른 페이지 로딩을 가능하게 합니다.

3. 라우팅 및 페이지 기반의 개발: Next.js는 파일 시스템을 기반으로 라우팅을 제공하며, 페이지마다 pages 디렉토리 안에 파일을 생성하여 쉽게 새로운 페이지를 추가할 수 있습니다.

4. 데이터 페칭: getServerSideProps 및 getStaticProps와 같은 함수를 사용하여 데이터를 미리 가져와서 페이지에 주입할 수 있습니다. 이를 통해 초기 데이터 로딩을 효율적으로 처리할 수 있습니다.

5. API Routes: Next.js는 API Routes를 제공하여 서버리스 함수처럼 작동하는 API 엔드포인트를 쉽게 생성할 수 있습니다.

6. CSS 모듈 지원: CSS 모듈을 사용하여 컴포넌트 스코프 내에서 스타일을 관리할 수 있습니다.

7. Hot Module Replacement (HMR): 개발 중에 코드 변경 사항을 실시간으로 반영하여 빠르게 개발할 수 있도록 도와줍니다.

8. 풍부한 플러그인 생태계: 다양한 플러그인과 확장 기능이 Next.js에는 내장되어 있어서 개발자가 더 효과적으로 작업할 수 있습니다.


## 셋팅
`npx create-next-app@latest`

## 시작하기

우선, 서버를 시작합니다.:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

사이트 들어가기 [http://localhost:3000](http://localhost:3000)

`app/page.js`를 수정해서 사이트를 수정할 수 있습니다. 파일을 수정하면 자동으로 사이트가 업데이트됩니다.

## 더 알아보기

Next.js를 더 알아보기위한 방법:

- [Next.js Documentation](https://nextjs.org/docs) - Next.js 문서 살펴보기
- [Learn Next.js](https://nextjs.org/learn) - Next.js 튜토리얼