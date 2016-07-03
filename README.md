> A basic boilerplate for publishing an npm module written in es2015


# Instructions:


- Clone the repo into a new directory :

  `$ git clone https://github.com/Thr1ve/base-es2015-npm awesome-module-name && cd awesome-module-name`


- Update the `origin` repo to point to your github repo :

  `$ git remote set-url origin https://github.com/yourUserName/awesome-module-name`


- Modify `package.json` as needed with the information for your new module

    - Note: Be sure that `main` in your `package.json` is set to `lib/index.js`


- Write code in the `src` directory


- When you're ready, publish your module to npm :

  `$ npm login`

  `$ npm publish --access public`
