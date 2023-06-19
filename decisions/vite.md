Here is an example architecture decision record for using Vite.js:

# Use Vite.js

Date: 2023-06-19

Status: Accepted

## Context

We are building a client side rendering frontend web application in React and need to choose a build tool. Vite has been proposed as an option for faster development builds and a simpler configuration compared to other tools like create-react-app (Webpack) which is not user-friendly when it comes to customization.

While Webpack has been dominant bundler in the past few years, Vite is gaining popularity due to its simplicity and speed. Major UI frameworks has adopted Vite as their default build tool (Vue, Svelte, Solid and Qwik). As of writing, React team does not recommend create-react-app for production use and instead recommends Next.js or Remix. However, Next.js and Remix are not suitable for our use case as we need to build a single page application (SPA) and not a server side rendered (SSR) application. Vite.js is also listed as an recommended option for React in the official documentation.

## Decision

We will use Vite as our build tool for the frontend application. Its simplicity and speed will help us to build a better developer experience for our users.

## Consequences

Extremely fast builds - thanks to esbuild and native ES module support in modern browsers that power Vite.

Simple and unopinionated - Easy to configure and extend via plugin API

Dev server - Built-in dev server supports hot module replacement (HMR) out of the box.
