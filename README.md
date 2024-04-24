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

# Step 2: Create a repository in Code Commit
Repository name: mlops-jan24
![image](https://github.com/nibinkjoseph/MLops-project1-AWS-Codecommit/assets/63180074/bcf07bb9-5d76-4497-a001-811b6a3ddd6a)
![image](https://github.com/nibinkjoseph/MLops-project1-AWS-Codecommit/assets/63180074/a63010af-6ad5-4d93-b57f-a66c17bc47fb)

This is the Repository view:
![image](https://github.com/nibinkjoseph/MLops-project1-AWS-Codecommit/assets/63180074/0f1ddb15-9a68-4b38-b7c6-72109f74321c)

Copy HTTPS

https://git-codecommit.us-east-1.amazonaws.com/v1/repos/mlops-jan24

This is the github folder:

https://github.com/03sarath/aws-devops/tree/master

# Step 3: Now clone it to the working directory

git clone https://github.com/03sarath/aws-devops.git

After cloning the repository and checking for status by git status command we see that it is in main branch thats the reason we dont see any file in the working directory. But checkout to master branch using the command git checkout master








