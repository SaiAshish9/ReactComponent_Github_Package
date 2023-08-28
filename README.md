```
.npmrc

@saiashish9:registry=https://npm.pkg.github.com

Repo 1:
npm install --save-dev @babel/core @babel/cli @babel/preset-env 
npm install -save @babel/polyfill

npm run build
npm login --scope=@NAMESPACE --auth-type=legacy --registry=https://npm.pkg.github.com
npm publish

Repo 2:
npm login --scope=@NAMESPACE --auth-type=legacy --registry=https://npm.pkg.github.com
npm i @saiashish9/sai-components@0.1.1
````
