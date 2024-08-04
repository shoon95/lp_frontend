# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

FEAT : 새로운 기능 추가
FIX : 버그 수정
DOCS : 문서 수정 및 추가
STYLE : 코드 스타일 관련 변경(코드 포매팅, 세미콜론 누락 등)
REFACTOR : 코드 리팩토링
TEST : 테스트 코드, 리팩토링 테스트 코드 추가
CHORE : 빌드 task 수정, 패키지 매니저 수정(.gitignore 수정 같은 경우)