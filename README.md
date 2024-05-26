# Next.js 14 Notion

<!-- GitHub badges -->

[![Latest release](https://img.shields.io/github/v/release/ladunjexa/nextjs14-notion?label=Latest%20release&style=social)](https://github.com/ladunjexa/nextjs14-notion/releases/tag/v0.1.0)
[![Stars](https://img.shields.io/github/stars/ladunjexa/nextjs14-notion?style=social)](https://github.com/ladunjexa/nextjs14-notion/stargazers)
[![Fork](https://img.shields.io/github/forks/ladunjexa/nextjs14-notion?style=social)](https://github.com/ladunjexa/nextjs14-notion/forks)
[![GitHub commits](https://img.shields.io/github/commit-activity/t/ladunjexa/nextjs14-notion?style=social&logo=github)](https://github.com/ladunjexa/nextjs14-notion/commits)
[![Pull requests](https://img.shields.io/github/issues-pr/ladunjexa/nextjs14-notion?style=social&logo=github)](https://github.com/ladunjexa/nextjs14-notion/pulls)

![demo](https://i.ibb.co/Qm9fb95/nextjs14-notion-vercel-app-1.png)

[![ladunjexa](https://custom-icon-badges.demolab.com/badge/made%20by%20-ladunjexa-556bf2?logo=github&logoColor=white&labelColor=101827)](https://github.com/luadnjexa)
[![License](https://img.shields.io/github/license/ladunjexa/nextjs14-notion?color=dddddd&labelColor=000000)](https://github.com/ladunjexa/nextjs14-notion/blob/main/LICENSE)
[![Top Language](https://img.shields.io/github/languages/top/ladunjexa/nextjs14-notion?logo=github&logoColor=%23007ACC&label=TypeScript)](https://www.typescriptlang.org/)
[![Contributors](https://img.shields.io/github/contributors/ladunjexa/nextjs14-notion?style=flat&color=orange&label=Contributors)](https://github.com/ladunjexa/nextjs14-notion/graphs/contributors)
![Release](https://img.shields.io/github/release/ladunjexa/nextjs14-notion.svg)
![PRs](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=shields)
![deployment](https://img.shields.io/github/deployments/ladunjexa/nextjs14-notion/Production?logo=vercel&label=Website)
[![Known Vulnerabilities](https://snyk.io/test/github/ladunjexa/nextjs14-notion/badge.svg)](https://snyk.io/test/github/ladunjexa/nextjs14-notion)

## 🌐 Live Demo

Explore the live demonstration of the project: [nextjs14-notion](https://nextjs14-notion.vercel.app/)

## 📝 Description

**Notion** is a Notion-like application built with Next.js 14, React, Convex, Tailwind, Clerk, and EdgeStore. It is a real-time database and Notion-style editor that allows you to create, edit, and delete documents. It also allows you to publish your note to the web.

<details><summary><b>Folder Structure</b></summary>

```bash
nextjs14-notion/
├── app/
├   ├── (main)/
├   ├   ├── (routes)/
├   ├   ├   └── documents/
├   ├   ├       ├── page.tsx
├   ├   ├       └── [documentId]/
├   ├   ├           └── page.tsx
├   ├   ├── _components/
├   ├   ├   ├── banner.tsx
├   ├   ├   ├── document-list.tsx
├   ├   ├   ├── item.tsx
├   ├   ├   ├── menu.tsx
├   ├   ├   ├── navbar.tsx
├   ├   ├   ├── navigation.tsx
├   ├   ├   ├── publish.tsx
├   ├   ├   ├── title.tsx
├   ├   ├   ├── trash-box.tsx
├   ├   ├   └── user-item.tsx
├   ├   └── layout.tsx
├   ├── (marketing)/
├   ├   ├── _components/
├   ├   ├   ├── footer.tsx
├   ├   ├   ├── heading.tsx
├   ├   ├   ├── heroes.tsx
├   ├   ├   ├── logo.tsx
├   ├   ├   └── navbar.tsx
├   ├   ├── layout.tsx
├   ├   └── page.tsx
├   ├── (public)/
├   ├   ├── (routes)/
├   ├   ├   └── preview/
├   ├   ├       └── [documentId]/
├   ├   ├           └── page.tsx
├   ├   ├── layout.tsx
├   ├── api/
├   ├   └── edgestore/
├   ├       └── [...edgestore]/
├   ├           └── route.ts
├   ├── favicon.ico
├   ├── globals.css
├   ├── error.tsx
├   ├── not-found.tsx
├   └── layout.tsx
├── components/
├   ├── modals/
├   ├   ├── confirm-modal.tsx
├   ├   ├── cover-image-modal.tsx
├   ├   └── settings-modal.tsx
├   ├── providers/
├   ├   ├── convex-provider.tsx
├   ├   ├── modal-provider.tsx
├   ├   └── theme-provider.tsx
├   ├── shared/
├   ├   ├── cover.tsx
├   ├   ├── editor.tsx
├   ├   ├── icon-picker.tsx
├   ├   ├── mode-toggle.tsx
├   ├   ├── search-command.tsx
├   ├   ├── single-image-dropzone.tsx
├   ├   ├── spinner.tsx
├   ├   └── toolbox.tsx
├   └── ui/ (generated by shadcn-ui)
├       ├── alert-dialog.tsx
├       ├── avatar.tsx
├       ├── button.tsx
├       ├── command.tsx
├       ├── dialog.tsx
├       ├── dropdown-menu.tsx
├       ├── input.tsx
├       ├── label.tsx
├       ├── popover.tsx
├       └── skeleton.tsx
├── convex/
├   ├── generated/ (generated by convex)
├   ├── auth.config.js
├   ├── documents.ts
├   ├── schema.ts
├   └── tsconfig.json
├── hooks/
├   ├── use-cover-image.ts
├   ├── use-origin.ts
├   ├── use-scroll-top.ts
├   ├── use-search.ts
├   └── use-settings.ts
├── lib/
├   ├── edgestore.ts
├   └── utils.ts
├── public/
├   ├── next.svg
├   ├── vercel.svg
├   └── assets/
├       ├── icons/[[...]].png
├       └── images/[[...]].{svg,png}
├── .eslintrc.json
├── .gitignore
├── README.md
├── components.json
├── next.config.js
├── package.json
├── postcss.config.js
├── tailwind.config.ts
└── tsconfig.ts
```

</details>

## 📖 Table of Contents

<details><summary>Table of Contents</summary>

- [Live Demo](#-live-demo)
- [Description](#-description)
- [Technologies Used](#-technologies-used)
- [Get Started](#-get-started)
  - [Prerequisites](#-prerequisites)
  - [Installation and Run Locally](#-installation-and-run-locally)
  - [Scripts](#-scripts)
- [Environment Variables](#-environment-variables)
- [Deployment](#-deployment)
  - [Deploy to production (manual)](#-deploy-to-production-manual)
  - [Deploy on Vercel (recommended)](#-deploy-on-vercel-recommended)
  - [Deploy on Netlify](#-deploy-on-netlify)
- [Features](#-features)
- [Contributing](#-contributing)
  - [Bug / Feature Request](#-bug--feature-request)
- [Acknowledgements](#-acknowledgements)
- [References](#-references)
- [Contact Us](#-contact-us)
- [License](#-license)

</details>

## ✨ Technologies Used

<details><summary><b>Notion</b> is built using the following technologies:</summary>

- [TypeScript](https://www.typescriptlang.org/): TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.
- [Next.js](https://nextjs.org/): Next.js is a React framework for building server-side rendered and statically generated web applications.
- [Tailwind CSS](https://tailwindcss.com/): Tailwind CSS is a utility-first CSS framework for rapidly building custom user interfaces.
- [Convex](https://convex.dev/): Convex is a TypeScript-first ORM for Node.js and the browser.
- [Clerk](https://clerk.dev/): Clerk is a developer-first identity and user management service.
- [ESLint](https://eslint.org/): ESLint is a static code analysis tool for
  identifying problematic patterns found in JavaScript code.
- [Prettier](https://prettier.io/): Prettier is an opinionated code formatter.
- [Shadcn-UI](https://ui.shadcn.com/): Shadcn UI is a React UI library that helps developers rapidly build modern web applications.
- [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction): Zustand is a small, fast and scalable bearbones state-management solution.
- [BlockNote](https://blocknote.dev/): BlockNote is a Notion-like editor for React.
- [Zod](https://zod.dev/): Zod is a TypeScript-first schema declaration and validation library.
- [Vercel](https://vercel.com/): Vercel is a cloud platform for frontend developers, providing the frameworks, workflows, and infrastructure to build a faster, more personalized Web.

</details><br/>

[![Technologies Used](https://skillicons.dev/icons?i=ts,nextjs,tailwind,vercel)](https://skillicons.dev)

## 🧰 Get Started

To get this project up and running in your development environment, follow these step-by-step instructions.

### 📋 Prerequisites

In order to install and run this project locally, you would need to have the following installed on your local machine.

- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/get-npm)
- [Git](https://git-scm.com/downloads)

### ⚙️ Installation and Run Locally

**Step 0:**

Note :bangbang: the application uses Convex for ORM, therefore, you need to create Convex account [here](https://convex.dev/) and sets the `CONVEX_DEPLOY_KEY` and `NEXT_PUBLIC_CONVEX_URL` environment variables in `.env` file.

Note :bangbang: the application uses Clerk for Authentication and User Management, therefore, you need to create Clerk account [here](https://clerk.dev/) and sets the `CLERK_PUBLISHABLE_KEY` and `CLERK_SECRET_KEY` environment variables in `.env` file.

Note :bangbang: the application uses EdgeStore for file uploads, therefore, you need to create EdgeStore account [here](https://edgestore.dev/) and sets the `EDGE_STORE_ACCESS_KEY` and `EDGE_STORE_SECRET_KEY` environment variables in `.env` file.

Also, you need to create a JWT template in Clerk and define the JWKS Endpoint as a provider inside `convex/auth.config.js` file.

**Step 1:**

Download or clone this repo by using the link below:

```bash
git clone https://github.com/ladunjexa/nextjs14-notion.git
```

**Step 2:**

Execute the following command in the root directory of the downloaded repo in order to install dependencies:

```bash
npm install
```

**Step 3:**

Execute the following command in order to run the development server locally:

```bash
npm run dev
```

**Step 4:**

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### 📜 Scripts

All scripts are defined in the `package.json` file. Here is a list of all scripts:

| Script          | Action                                      |
| :-------------- | :------------------------------------------ |
| `npm install`   | Installs dependencies                       |
| `npm run dev`   | Starts local dev server at `localhost:3000` |
| `npm run build` | Build your production site to `./dist/`     |
| `npm run start` | Start your production site locally          |
| `npm run lint`  | Run ESLint                                  |

## 🔒 Environment Variables

Environment variables[^6] can be used for configuration. They must be set before running the app.

> [Environment variables](https://en.wikipedia.org/wiki/Environment_variable) are variables that are set in the operating system or shell, typically used to configure programs.

**Notion** uses [Convex](https://appwrite.io), and [Clerk](https://clerk.com) as external services. You need to create an accounts on Convex and Clerk and get the required credentials to run the app.

Create a `.env` file in the root directory of the project and add the following environment variables:

```env
CONVEX_DEPLOY_KEY=<CONVEX_DEPLOY_URL>
NEXT_PUBLIC_CONVEX_URL=<NEXT_PUBLIC_CONVEX_URL>

CLERK_PUBLISHABLE_KEY=<CLERK_PUBLISHABLE_KEY>
CLERK_SECRET_KEY=<CLERK_SECRET_KEY>

EDGE_STORE_ACCESS_KEY=<EDGE_STORE_ACCESS_KEY>
EDGE_STORE_SECRET_KEY=<EDGE_STORE_SECRET_KEY>
```

## 🚀 Deployment

#### Deploy to production (manual)

You can create an optimized production build with the following command:

```bash
npm run build
```

#### Deploy on Vercel (recommended)

The easiest way to deploy this Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fladunjexa%2Fnextjs14-notion)

#### Deploy on Netlify

You can also deploy this Next.js app with [Netlify](https://www.netlify.com/).

[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ladunjexa/nextjs14-notion)

Check out [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## 💡 Features

- Real-time database 🔗
- Notion-style editor 📝
- Light and Dark mode 🌓
- Infinite children documents 🌲
- Trash can & soft delete 🗑️
- Authentication 🔐
- File upload
- File deletion
- File replacement
- Icons for each document (changes in real-time) 🌠
- Expandable sidebar ➡️🔀⬅️
- Full mobile responsiveness 📱
- Publish your note to the web 🌐
- Fully collapsable sidebar ↕️
- Landing page 🛬
- Cover image of each document 🖼️
- Recover deleted files 🔄📄

## 🔧 Contributing

[![contributors](https://contrib.rocks/image?repo=ladunjexa/nextjs14-notion)](https://github.com/ladunjexa/nextjs14-notion/graphs/contributors)

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

To fix a bug or enhance an existing module, follow these steps:

1. Fork the repo
2. Create a new branch (`git checkout -b improve-feature`)
3. Make the appropriate changes in the files
4. Commit your changes (`git commit -am 'Improve feature'`)
5. Push to the branch (`git push origin improve-feature`)
6. Create a Pull Request 🎉

### 📩 Bug / Feature Request

If you find a bug (failure of a module to execute its intended function), kindly open an issue [here](https://github.com/ladunjexa/nextjs14-notion/issues/new) by including the issue with a title and clear description.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/ladunjexa/nextjs14-notion/issues/new). Please include sample queries and their corresponding results.

## 💎 Acknowledgements

I'd like to express my gratitude to the following people who helped me with this
project and made it possible:

- [Clerk](https://clerk.dev/)
- [Convex](https://convex.dev/)
- [EdgeStore](https://edgestore.dev/)
- [BlockNote](https://blocknote.dev/)
- [Shadcn UI](https://ui.shadcn.com/)
- [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction)
- [useHooks TS](https://usehooks-ts.com/)
- [Sonner](https://sonner.emilkowal.ski/)
- [Next Themes](https://ui.shadcn.com/docs/dark-mode/next)
- [Emoji Picker React](https://www.npmjs.com/package/emoji-picker-react)
- [React Dropzone](https://react-dropzone.js.org/)
- [React Textarea Autosize](https://www.npmjs.com/package/react-textarea-autosize)
- [Vercel](https://vercel.com/)
- [CodeWithAntonio](https://www.codewithantonio.com/)

## 📚 References

CodeWithAntonio. (2023). [Fullstack Notion Clone: Next.js 13, React, Convex, Tailwind](https://www.codewithantonio.com/projects/notes-app). E-Learning.

## 📞 Contact Us

[![Telegram](https://img.shields.io/badge/Telegram-@ladunjexa-2CA5E0?style=social&logo=telegram&logoColor=000000)](https://t.me/ladunjexa)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ladunjexa-blue?style=flat&logo=linkedin&logoColor=b0c0c0&labelColor=363D44)](https://www.linkedin.com/in/lironabutbul)
[![Instagram](https://img.shields.io/badge/Instagram-ladunjexa-grey?style=flat&logo=instagram&logoColor=b0c0c0&labelColor=8134af)](https://www.instagram.com/ladunjexa)
[![Discord](https://img.shields.io/badge/Discord-ladunjexa-7289da?style=flat&logo=discord&logoColor=b0c0c0&labelColor=2c2f33)](https://discord.com/users/827996364331810816)

<!-- [![Twitter](https://img.shields.io/twitter/follow/ladunjexa.svg?style=social)](https://twitter.com/intent/follow?screen_name=ladunjexa) -->

## 📋 License

**Notion** is open source software [licensed as MIT](https://opensource.org/license/mit/) and is free to use — See [LICENSE](https://github.com/ladunjexa/nextjs14-notion/blob/main/LICENSE) for more details.
