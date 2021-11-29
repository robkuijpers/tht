## Installation
Use NVM for Node installation
> npm install -g @ionic/cli
> ionic start
> cd tht
> ng serve --lab

### ios with capacitor
Setup xcode see https://ionicframework.com/docs/developing/ios
> ionic capacitor add ios
> ionic capacitor open ios
> ionic capacitor copy ios
> ionic capacitor run ios -l --external

### android with capacitor
Setup android studio see https://ionicframework.com/docs/developing/android
> ionic capacitor add android
> ionic capacitor copy android
> ionic capacitor run android -l --host=YOUR_IP_ADDRESS

### add prject to github
See github instructions when creating new repo

### use other github repo to setup nestjs or use mono repo with nx
https://devdactic.com/ionic-nest-image-upload-api/
https://devdactic.com/ionic-nest-image-upload-capacitor/

https://ionicframework.com/blog/full-stack-typescript-with-ionic-angular-and-nestjs-part-1/


## deploy to AWS
Use Github actions and a Docker container to an Amazon ECS service powered by AWS Fargate or Amazon EC2
