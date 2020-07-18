---
title: "0 - Create react App"
tags: ""
---

### TOOLSCHAIN (Chaine d'outils)

##### RECOMMENDED TOOLCHAIN

-   If you creating a new **[single-page](https://reactjs.org/docs/glossary.html#single-page-application)** app, use ** [Create React App](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app) **.
-   If you’re building a server-rendered website with **Node.js**, try **[Next.js](https://nextjs.org/learn/)**.
-   If you’re building a static content-oriented website, try **[Gatsby](https://www.gatsbyjs.org/docs/)**
-   If you’re building a component library or integrating with an existing codebase, try More Flexible Toolchains.

###### FLEXIBLE TOOLCHAINS:

-   **[Neutrino](https://neutrinojs.org/)** combines the power of webpack with the simplicity of presets, and includes a preset for React apps and React components.
-   **[Nx](https://nx.dev/react)** is a toolkit for full-stack monorepo development, with built-in support for React, Next.js, Express, and more.
-   **[Parcel](https://parceljs.org/)** is a fast, zero configuration web application bundler that works with React.
-   **[Razzle](https://github.com/jaredpalmer/razzle)** is a server-rendering framework that doesn’t require any configuration, but offers more flexibility than Next.js.

> **[WEBPACK](https://webpack.js.org/):** webpack is used to compile JavaScript modules  
> **[RFC](https://github.com/reactjs/rfcs)**: The RFC (request for comments) process is intended to provide a consistent and controlled path for new features to enter the project.

##### CREATE REACT APP

To create a new app, you may choose one of the following methods:

[Here the doc](https://create-react-app.dev/docs/getting-started)

###### npx:

    npx create-react-app my-app

###### npm

    npm init react-app my-app

###### Yarn

    yarn create react-app my-app

###### Selecting a template

    npx create-react-app my-app --template [template-name]

> You can find a list of available templates by searching for "[cra-template-\*](https://www.npmjs.com/search?q=cra-template-*)" on npm.
