# Resource Management Game Simulator

工場シミュレーションやコロニーシミュレーションのようなゲームにおけるリソースの生産や加工といった行動を、ガントチャートのように時間軸上でタスクを配置しながら計画・検証することを目的としたツール

## SvelteKit (frontend)

This repository uses SvelteKit (created via `sv`) with Tailwind CSS, Prettier and ESLint.

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```sh
# create a new project
npx sv create my-app
```

To recreate this project with the same configuration:

```sh
# recreate this project
npx sv@0.16.3 create --template minimal --types ts --add prettier eslint tailwindcss="plugins:none" --install npm rmgs
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```sh
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```sh
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
