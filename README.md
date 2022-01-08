# tsnode-exp

Exploring using Typescript and Nodejs

A repo for going through a walkthrough to set up Typescript and Nodejs.

From: https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c

## Log

1. Set up repo
2. Edit Readme & commit
3. `npm-init -y`
4. npm install --save-dev typescript
5. create `tsconfig.json`
    * Change outDir to `dist` since that's more standard.
6. add basic index.ts
7. add build-line to package.json
    * Mess up comma in JSON. JSON is almost a perfect serialization format.
      It's too bad it has all these small warts.
8. add tslint
9. .prettierrc
    * I really want the uber builder vim plugin
