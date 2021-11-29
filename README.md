<p align="center">
  <a href="https://www.gatsbyjs.com/">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby starter with Yarn 3, Tailwind CSS, Firebase Hosting and some helpers
</h1>

## 🖖 Hello

This is a starter repo with:

- Gatsby.js
- Firebase Hosting
- TailwindCSS
- Yarn 3
- Prettier
- ESLint
- Husky + Lint-Staged

## 🚀 Quick start

1. **Clone this repo.**

   Clone or fork this repo to start a new project.

2. **Start developing.**

   Navigate into your new site’s directory and start it up.

   ```shell
   cd my-gatsby-site/
   yarn run develop
   ```

3. **Open the code and start customizing!**

   Your site is now running at http://localhost:8000!

   Edit `src/pages/index.js` to see your site update in real-time!

## 🔥 Firebase Hosting

This project uses our own Firebase project for hosting. To deploy - create your own Firebase project, update firebase project ID in `.firebaserc`, and follow steps described in [docs](https://firebase.google.com/docs/hosting/quickstart).

If you are new to deploying Gatsby.js website to Firebase Hosting, try to read this acrticle [Deploy Gatsby.js website to Firebase Hosting](https://ryndia.me/deploy-gatsby-js-website-to-firebase-hosting/).

If it did not help, try to

1. Delete following files and folders from project:
   - `.github/workflows` folder
   - `.firebaserc` file
   - `firebase.json` file
2. Execute `firebase init hosting` in shell

## ☕️ Upgrade dependicnes

We use [plugin-interactive-tool](https://yarnpkg.com/api/modules/plugin_interactive_tools.html) for `yarn` for intercative dependencies updates/upgrades. To use it execute

```shell
yarn upgrade
```

## 📖 Learn more

- [Gatsby docs](https://www.gatsbyjs.com/docs)
- [Gatsby Plugin Library](https://www.gatsbyjs.com/plugins)
- [Gatsby Cheat Sheet](https://www.gatsbyjs.com/docs/cheat-sheet/)
- [TailwindCSS docs](https://tailwindcss.com/docs)
- [TailwindCSS Official UI Kit](https://tailwindui.com/)
- [Firebase Hosting](https://firebase.google.com/docs/hosting)
- [Firebase Hosting with GitHub](https://firebase.google.com/docs/hosting/github-integration)
- [Gatsby.js deployment to Firebase Hosting](https://ryndia.me/deploy-gatsby-js-website-to-firebase-hosting/)
