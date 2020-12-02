# Serverless Localstack with Typescript via Webpack

This is an example repo showing how serverless-webpack does not work with serverless-localstack

## Notes

How to recreate this:

1. `serverless create --template aws-nodejs-typescript --path ls-lambda-ts-webpack`
2. `cd ls-lambda-ts-webpack && npm i && npm i --save-dev serverless-localstack`
3. Edit line in serverless.yml to add the `localstack` section in serverless.yml
4. `serverless deploy --stage=local`
