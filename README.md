# NxMonorepoTestEscolaTi

## Comands

- npx create-nx-workspace@latest nx-monorepo-escola-ti
- ✔ Which stack do you want to use? · none
- ✔ Package-based monorepo, integrated monorepo, or standalone project? · integrated
- ✔ Enable distributed caching to make your CI faster · Yes
- npm i -D @nx/angular
- npx nx g @nx/angular:application --name=web --directory=front --routing=true --style=scss --no-interactive
- npm i -D husky lint-staged
- npm pkg set scripts.prepare="husky install"
- npm run prepare
- npx husky add .husky/pre-commit "npx lint-staged"
- npm i -D @nx/nest
