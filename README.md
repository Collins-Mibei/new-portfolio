<div align="center">
  <img alt="Logo" src="https://github.com/Collins-Mibei/new-portfolio/blob/main/src/images/logo.png" width="150" />
</div>

<h1 align="center">
Collins Mibei's Portfolio Website
</h1>

<p align="center">
  This is my personal portfolio website built with <a href="https://www.gatsbyjs.org/" target="_blank">Gatsby</a>
</p>

<p align="center">
  Adapted from <a href="https://brittanychiang.com/" target="_blank">Brittany Chiang's</a> Design on Github and can be found <a href="https://github.com/bchiang7/v4" target="_blank">here</a>
</p>

![demo](https://github.com/Collins-Mibei/new-portfolio/blob/main/src/images/demo.png)

## 🛠 Installation & Set Up

1. Install the Gatsby CLI

   ```sh
   npm install -g gatsby-cli
   ```

2. Install and use the correct version of Node using [NVM](https://github.com/nvm-sh/nvm)

   ```sh
   nvm install
   ```

3. Install dependencies

   ```sh
   yarn install
   ```

4. Start the development server

   ```sh
   yarn start
   ```

## 🚀 Building and Running for Production

1. Generate a full static production build

   ```sh
   yarn run build
   ```

1. Preview the site as it will appear once deployed

   ```sh
   yarn run serve
   ```

## 🧐 What's inside?

A quick look at the top-level files and directories in this project.

    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    ├── README.md
    └── yarn.lock

1. **`/node_modules`**: The directory where all of the modules of code that your project depends on (npm packages) are automatically installed.

2. **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser), like your site header, or a page template. “Src” is a convention for “source code”.

3. **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

4. **`.prettierrc`**: This is a configuration file for a tool called [Prettier](https://prettier.io/), which is a tool to help keep the formatting of your code consistent.

5. **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://next.gatsbyjs.org/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

6. **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://next.gatsbyjs.org/docs/gatsby-config/) for more detail).

7. **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby node APIs](https://next.gatsbyjs.org/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

8. **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://next.gatsbyjs.org/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

9. **`LICENSE`**: Gatsby is licensed under the MIT license.

10. **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. (You won’t change this file directly).

11. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

12. **`README.md`**: A text file containing useful reference information about your project.

13. **`yarn.lock`**: [Yarn](https://yarnpkg.com/) is a package manager alternative to npm. You can use either yarn or npm, though all of the Gatsby docs reference npm. This file serves essentially the same purpose as `package-lock.json`, just for a different package management system.
