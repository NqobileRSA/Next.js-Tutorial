# Next.js Tutorial

- What is Next.js?

  > An official react.js framework that allows to create `pre-rendered` react
  > web applications. Offers both server side rendering and static site
  > generation.

  <!-- ----------------------------------------------- -->

- What is it used for?

  > server side rendering : "websites are rendered in the server before served
  > to the client", static site generation : "a static html file is generated
  > for each page at build time, and served directly by the web server."

  <!-- ----------------------------------------------- -->

- Why should you use it?

  > Pre-rendering improves performance. Better search engine optimization.

  <!-- ----------------------------------------------- -->

- How is it different from React.js?
  > React uses client side rendering.

# Installation and setup

> Install node v10.01 + Open terminal on vscode. Run : `npx create-next-app`
> accept all the prompts.

# Folder structure

| `app` : > layout.tsx : Defines the layout of your application, including
headers, footers, and other shared components > pages.tsx : contains react
components that a rendered as individual pages, each page becomes a route. |
`components` : reusable components within the application. | `public` : contains
assests served statically directly by the web server (not processed by next.js)
| `next.config.js` : configure the next app. | `package.json` : meta data and
dependecies. | `lib` : third party libraries || custom libraries. | `utils` :
helper functions || utility functions

# Pages and Routes

|
