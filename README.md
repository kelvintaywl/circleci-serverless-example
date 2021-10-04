# CircleCI Serverless Example

## How I created the Serverless project?

```sh
# use the right Node runtime via NVM
nvm use

# install deps, including Serverless Framework
npm install

# create a folder for our FaaS project
mkdir -p src/services/core
cd src/services/core

# created a boilerplate project
npx serverless create --template aws-nodejs
```
