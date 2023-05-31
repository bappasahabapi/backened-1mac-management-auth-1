###    `mac-management-auth-1`

---

To run the file in your computer

1. [clone the project](https://github.com/bappasahabapi/mac-management-auth-1.git)

2. `cd mac-managemetnt-auth-1`

3. ` yarn install`

4. `yarn start `




### UM-6 👍Create User Interface and Modules

[visit this doc](https://mongoosejs.com/docs/typescript.html)

**Create:**

make `interface` -> `sechema` --> `model`-->`service`-->`controller`-->`route`

  users.interface.ts
  users.model.ts
  user.service.ts
  user.utils.ts
  user.controller.ts




**Step:1**

 `  yarn add typescript --dev`
  ` yarn add express mongoose`
  ` npm init`

**Next we configure the typescript file. so we need a ts config file.**

` tsc --init`

in the tsconfig.json file enalble the ./src and ./dist in source and ouotdir.

`yarn add dotenv`

---

`yarn add -D @types/express`

To run the file go to `ts-node-dev` documentation

`yarn add --dev ts-node-dev`
`yarn add cors`

Then add this to the package.json script file

    ts-node-dev --respawn --transpile-only server.ts

```js
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "ts-node-dev --respawn --transpile-only src/server.ts"
  },
```

run 👍

    yarn start
    
---
[Read this blog step by step](https://blog.logrocket.com/linting-typescript-eslint-prettier/)

**Install ESLint:**
`npm install eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin --save-dev`
`yarn add eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin --save-dev`


**Install Prettier**
yarn add -D prettier

npm install --save-dev eslint-config-prettier

**Install Husky**

`yarn add husky --dev`

`yarn husky install`

`yarn husky add .husky/pre-commit "npm test"`

`yarn add -D lint-staged`

---
