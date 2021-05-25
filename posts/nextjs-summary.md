---
title: 'nextjs-study-summary'
date: '2020-05-25'
---

# 요약 : Next.js를 사용하는 주 목적

- `SEO(서치엔진 최적화)`와 `SSG(정적 파일 생성) - pre rendering`를 위함임

  - 매번 사용자 요청에 의해 다시 그릴 필요가 없는 경우 미리 빌드 파일에 포함하여 배포함

- "사용자의 요청에 앞서 이 페이지를 미리 렌더링 할 수 있습니까? 가능하다면 SSG
- 정적 생성은 사용자의 요청에 앞서 페이지를 미리 렌더링 할 수없는 경우 좋은 생각이 아닙니다.
- 페이지에 자주 업데이트되는 데이터가 표시되고 모든 요청에 따라 페이지 콘텐츠가 변경 될 수 있습니다.
- 그렇지 않으면 `SSR` 혹은 `SPA` 방식의 클라이언트 측 렌더링

![ssr](https://nextjs.org/static/images/learn/data-fetching/server-side-rendering-with-data.png)
![csr](https://nextjs.org/static/images/learn/data-fetching/client-side-rendering.png)

## Next.js는 Web Server 구축을 위한 프레임워크임

## 다양한 개발자 편의 기능 제공

![dynamic routing](https://nextjs.org/static/images/learn/dynamic-routes/how-to-dynamic-routes.png)

- An intuitive [page-based](https://nextjs.org/docs/basic-features/pages) routing system (with support for [dynamic routes](https://nextjs.org/docs/routing/dynamic-routes))
- [Pre-rendering](https://nextjs.org/docs/basic-features/pages#pre-rendering), both [static generation](https://nextjs.org/docs/basic-features/pages#static-generation-recommended) (SSG) and [server-side rendering](https://nextjs.org/docs/basic-features/pages#server-side-rendering) (SSR) are supported on a per-page basis
- Automatic code splitting for faster page loads
- [Client-side routing](https://nextjs.org/docs/routing/introduction#linking-between-pages) with optimized prefetching
- [Built-in CSS](https://nextjs.org/docs/basic-features/built-in-css-support) and [Sass support](https://nextjs.org/docs/basic-features/built-in-css-support#sass-support), and support for any [CSS-in-JS](https://nextjs.org/docs/basic-features/built-in-css-support#css-in-js) library
- Development environment with [Fast Refresh](https://nextjs.org/docs/basic-features/fast-refresh) support
- [API routes](https://nextjs.org/docs/api-routes/introduction) to build API endpoints with Serverless Functions
- Fully extendable

## Next.js는 코드 분할, 클라이언트 측 탐색 및 프리 페칭 (프로덕션 중)을 통해 애플리케이션을 자동으로 최적화하여 최상의 성능을 제공합니다.

- Resizing & optimizing images
