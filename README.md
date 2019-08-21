# Angular_Serverless_ng-toolkit-serverless

```
ng new serverlessApp
cd serverlessApp
ng add @ng-toolkit/universal
npm remove webpack webpack-cli
npm install webpack webpack-cli
ng add @ng-toolkit/serverless  —-provider aws
```
# update serverless.yml
* update aws region to us-east-1
* update nodejs version to 10.x


After successfully updating your project you can check if it is working correctly on lambda, by typing:
```
npm run build:serverless:deploy
```
When your domain is successfully provisioned, you can deploy your app to production:

```
npm run build:prod:deploy
```
