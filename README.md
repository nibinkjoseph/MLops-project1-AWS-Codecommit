# MLops-project1-AWS-Codecommit (Deploying a webapp)

Architecture:
![image](https://github.com/nibinkjoseph/MLops-project1-AWS-Codecommit/assets/63180074/1e83f94b-6924-4386-97a1-d35dab4234c0)


Code is sitting in  AWS CodeCommit
AWS CodePipeline is the CI tool
AWS CodeBuild is the CD tool

Add code to the codecommit, each team member will have a user account
# Step 1: Create a user
Create IAM user
![image](https://github.com/nibinkjoseph/MLops-project1-AWS-Codecommit/assets/63180074/4bfbddf9-241e-4075-8a39-2b17eb0e36da)

<b> User name: mlops-jan24

<b>User group name: mlops-jan24-group

<b>Policies: AdministratorAccess

![image](https://github.com/nibinkjoseph/MLops-project1-AWS-Codecommit/assets/63180074/c81a3400-6d23-4d43-b7ba-1a73ca94603e)

Go to HTTPS Git credentials for AWS CodeCommit (0) below and generate credentials
![image](https://github.com/nibinkjoseph/MLops-project1-AWS-Codecommit/assets/63180074/a8a587d1-7d75-45e8-a3af-f84ad0b8caac)

