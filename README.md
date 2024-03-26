Github Action for deploying NextJS Apps to AWS Elastic Beanstalk (found in github/workflows/uploadtoawseb.yml)

1. setup AWS EBeanstalk
2. setup AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY in Github Repository Secrets
3. setup all environmental variables or hardcode them, if you like
4. now when you push in to master, your github action is going to build your code, zip it and push it into your S3 and deploy it into Elastic Beanstalk

Using einaregilsson/beanstalk-deploy@v21
https://github.com/einaregilsson/beanstalk-deploy
