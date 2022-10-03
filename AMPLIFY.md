#

Init with github
check CI/CD deployment is working

sudo npm install -g @aws-amplify/cli
amplify configure

Step by step config AWS
 - IAM creation
 - accessKey pass


backend-environment setup
amplify pull --appId d23szvkyqyahwq --envName staging
Give access and login with aws-amplify

npm install aws-amplify @aws-amplify/ui-react
amplify add auth
amplify push --y


REMOVE:
---
amplify remove auth
