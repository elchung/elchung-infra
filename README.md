# Welcome to your CDK TypeScript project

Infrastructure setup using CDK to deploy resources for hosting elchung.com. Only manual step was certificate creation as
cdk was having issues creating + verifying using DNS when manual creation would instantly verify

I alos had to manually create an A record alias with cloudfront distribution

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template
