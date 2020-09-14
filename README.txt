https://docs.amplify.aws/start/q/integration/js



npm install -g @aws-amplify/cli
amplify configure
mkdir -p amplify-js-app/src && cd amplify-js-app
touch package.json index.html webpack.config.js src/app.js
npm start
amplify init


amplify add api
amplify push
amplify status
amplify console api

amplify add hosting
amplify publish

Deployed on:
Local - http://localhost:8081/

Cloud - https://dev.dm00u2jolt6pg.amplifyapp.com

S3 Cloud - http://amplifyjsapp-20200911104716-hostingbucket-dev.s3-website.ap-south-1.amazonaws.com/ 