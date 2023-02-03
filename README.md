# Pixelhop Vue 3 Starter Project

This is a starter project that is used a base for loads of [Pixelhop](https://pixelhop.io) front-end tutorials! 

This project contains the following pre-installed and configured to help you get up and running with our tutorials quicker so you can get on with the fun stuff!

- [Vite](https://vitejs.dev/) - Vite will provide us with front-end tooling.
- [PNPM](https://pnpm.io/) - PNPM has fast become our favourite package manager. Its just like NPM but faster!
- [Vue 3](https://vuejs.org) - We are spoilt for choice these days but Vue is still our fave frontend framework.
- [TailwindCSS](https://tailwindcss.com/) - The Marmitte of CSS frameworks! We love it and find it helps keep our projects consistant and allows us to be super productive.
- [ESlint](https://eslint.org/) + [Prettier](https://prettier.io/) - We want to avoid silly mistakes in our code and keep it nicely formatted.
- [Vue Router](https://router.vuejs.org/) - There's very few projects that don't need some kind of routing so we may as well set this up by defualt.

## Recommended IDE Setup

Install the following extensions if you don’t have them already:

- [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) - Vue Language Features. Make VSCode work nicely with .vue files
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Make VSCode work with ESLint
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Make VSCode work with Prettier

After installing the above extensions configure VSCode as follow to make all the extensions play nice.

Add this to you vscode settings json, or the your workspace settings json. (`cmd + shift + p` type ”Settings” and then select “Preferences: Open Setting JSON”)

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
  }
}
```

## How to use this starter project

Clone this project
```
git clone https://github.com/pixelhop/vue-starter.git <your-project-name>
```

Enter the new project folder
```
cd <your-project-name>
```

Initialise git
```
rm .rf .git && git init
```

Install dependencies. You may need to install pnpm first `npm i pnpm -g`
```
pnpm i
```


