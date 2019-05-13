# Build the Hungarian package

Works only with node v6 (node-sass is too old), I have v6.16.0 installed.

    nvm list
    nvm use 6.16.0

## Merge from original branch

    git pull https://github.com/firebase/firebaseui-web.git master

## Create Hungarian JS files

    npm run build build-js-hu
    npm run build build-npm-hu

## Create package

    npm pack --ignore-scripts

## Upload to npmjs.org

*Registry is set to npmjs.org in package.json.*

    npm publish --ignore-scripts

----

**Package created by**
Balazs Vamos