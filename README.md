# **Creation of [joshuaherman.tech](www.joshuaherman.tech)**

## [Next.js](https://nextjs.org/) & [Typscript](https://www.typescriptlang.org/)
[![Twitter](https://img.shields.io/twitter/follow/kumar_abhirup.svg?style=social&label=@kumar_abhirup)](https://twitter.com/kumar_abhirup/)[Many Thanks](https://github.com/KumarAbhirup/dockerized)
### Task-list for joshuaherman.tech

- [x] Create Docker container for website development
- [ ] Create Ansible role for complete deployment
- [ ] Site source will be hosted on Github
- [ ] Implement CSS tailwind
- [ ] Does it work?

### Start server and go to [localhost:3000](http://localhost:3000)

```bash
#Install all dependicies locally
cd joshuaherman.tech/packages/landingpage
npm install
cd joshuaherman.tech

docker-compose up
```

### Install Tailwind

```bash
npx tailwind init
```

### Configure Tailwind postcss.config.js

```javascript
module.exports = {
  plugins: ['tailwindcss', 'postcss-preset-env'],
};
```

NPM installs for PostCSS

- [PostCSS Purgecss]("https://www.npmjs.com/package/@fullhuman/postcss-purgecss")
- [tailwindcss](https://www.npmjs.com/package/tailwindcss)
- [autoprefixer](https://www.npmjs.com/package/autoprefixer)

### postcss.config.js
