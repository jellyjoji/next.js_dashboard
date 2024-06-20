## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

# Install

## npm upgrade

Node.js 업데이트는 Node.js 버전을 관리하는 n 이라는 모듈을 사용해서 할 수 있다.
sudo 권한으로 -g 전역에 n 모듈을 설치한다.

`sudo npm install -g n`

n 모듈을 사용하여 Nodejs 설치한다.

`sudo n stable`

n stable: 안정 버전
n latest: 최신 버전
n lts: lts 버전
n x.x.x: 특정 x.x.x 버전

`node -v`
Next.js 를 구동할수 있는 v20.14.0 버전으로 업그레이드된것을 확인한다.

`npm run dev`

http://localhost:3000/ 을 실행시킨다.

## Creating a new project

이제 새 dashboard 프로젝트를 생성해준다.

`npx create-next-app@latest nextjs-dashboard --use-npm --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example"`

`cd nextjs-dashboard`

`npm i`

`npm run dev`
