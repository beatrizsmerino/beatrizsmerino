# beatrizsmerino

## 🎯 Description

Main repository for the GitHub profile of [Beatriz Sopeña Merino](https://github.com/beatrizsmerino). It contains the profile `README.md` that is displayed on the GitHub profile page.

The profile includes coding stats powered by [WakaTime](https://github.com/wakatime) and visualizations generated with a self-hosted [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) instance on [Vercel](https://vercel.com/) to avoid the rate limits of the public instance.

The project includes automated workflows via [GitHub Actions](https://github.com/features/actions) for keeping stats up to date, along with code quality configuration using [Prettier](https://prettier.io/), [ESLint](https://eslint.org/) and [Commitlint](https://commitlint.js.org/).

## 🏗️ Developed with

![Bash](https://img.shields.io/badge/Bash-3D4648?style=for-the-badge&logo=gnu-bash&logoColor=white)
[![NVM](https://img.shields.io/badge/NVM-f4dd4b?style=for-the-badge&logo=npm&logoColor=333333)](https://github.com/nvm-sh/nvm)
[![NODE](https://img.shields.io/badge/-NODE-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/es/)
[![NPM](https://img.shields.io/badge/-NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://docs.npmjs.com/)

[![EditorConfig](https://img.shields.io/badge/-EditorConfig-FEFEFE?style=for-the-badge&logo=editorconfig&logoColor=black)](https://editorconfig.org/)
[![Prettier](https://img.shields.io/badge/-Prettier-1A2B34?style=for-the-badge&logo=prettier&logoColor=FFFFFF)](https://prettier.io/)
[![ESLint](https://img.shields.io/badge/-ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://eslint.org/)
[![Husky](https://img.shields.io/badge/-Husky-A8B1FF?style=for-the-badge)](https://typicode.github.io/husky/)
[![Commitlint](https://img.shields.io/badge/-Commitlint-FA6673?style=for-the-badge)](https://commitlint.js.org/)
[![Conventional Commits](https://img.shields.io/badge/-Conventional%20Commits-FE5196?style=for-the-badge&logo=conventionalcommits&logoColor=FEFEFE)](https://www.conventionalcommits.org)
[![lint-staged](https://img.shields.io/badge/-lint--staged-4B32C3?style=for-the-badge)](https://github.com/lint-staged/lint-staged)

[![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-000000?style=for-the-badge&logo=githubactions&logoColor=FFFFFF)](https://github.com/features/actions)
[![Vercel](https://img.shields.io/badge/-Vercel-0070F3?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)
[![GitHub Readme Stats](https://img.shields.io/badge/-GitHub%20Readme%20Stats-41B883?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anuraghazra/github-readme-stats)
[![WakaTime](https://img.shields.io/badge/-WakaTime-FF6347?style=for-the-badge&logo=wakatime&logoColor=white)](https://wakatime.com/)

## 🚀 Commands

### Install dependencies

Install all dependencies listed in `package.json`.

```bash
npm install
```

### Clean install dependencies

Remove `node_modules` and `package-lock.json` to reinstall from scratch.

```bash
npm run install:clean
```

### Lint after install

Runs automatically after `npm install` to run `npm run lint` on all project files.

```bash
npm run postinstall
```

### Set up Husky git hooks

Runs automatically after `postinstall` to enable `pre-commit` and `commit-msg` hooks of [Husky](https://typicode.github.io/husky/).

```bash
npm run prepare
```

### Lints and fixes files

Run [Prettier](https://prettier.io/) (`prettier:fix`) and [ESLint](https://eslint.org/) (`eslint:fix`) to format and lint all project files.

```bash
npm run lint
```

### Format files with Prettier

Format JSON, YAML and JS files with [Prettier](https://prettier.io/).

```bash
npm run prettier:fix
```

### Lint and fix files with ESLint

Lint and fix JSON and JS files with [ESLint](https://eslint.org/).

```bash
npm run eslint:fix
```

## 📄 License

This project is licensed under the `MIT` License, which allows free use, modification and distribution. See [LICENSE](LICENSE) for details.
