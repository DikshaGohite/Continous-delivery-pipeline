Creating a continous delivery pipeline to deploy Sample Node.js App to AWS Elastic Beanstalk

Services Used:
GitHub, AWS Elastic Beanstalk, AWS CodeBuild, AWS CodePipeline 

GitHub: GitHub is a version control platform allowing developers to store and manage their code and tracking any changes to it.

AWS Elastic Beanstalk: AWS Elastic Beanstalk, lets you can quickly deploy and manage applications in the AWS Cloud without having to learn about the infrastructure that runs those applications. Elastic Beanstalk reduces management complexity without restricting choice or control. You simply upload your application, and Elastic Beanstalk automatically handles the details of capacity provisioning, load balancing, scaling, and application health monitoring.

AWS CodeBuild: AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy.

AWS CodePipeline

Architecture
![Architecture-2](https://user-images.githubusercontent.com/128709137/233804655-48dac75a-57e0-4d97-a0ad-bf2f8448c3f9.PNG)

Step 1: 
Push the source code from your local to GitHub

Step 2: 
Navigate to AWS Elastic Beanstalk in console console.
Choose the orange Create Application button.
A new window appears, under the heading Application name, enter the name of your application
Select Node.js from the Platform dropdown menu. This selection should automatically fill in the Platform branch and Platform version menus
Confirm that the radio button next to Sample application is selected
Imp: Keep all the other settings as default to stay within free tier, review the changes and click create 
Within few minutes, your application will be launched, to test your sample web app select the link under the name of your environment.

step 3:

step 4:

step 5:
