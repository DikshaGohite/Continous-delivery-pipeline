Project Description: Creating a continous delivery pipeline to deploy Sample Node.js App to AWS Elastic Beanstalk and this continuous delivery pipeline will automatically deploy the web application whenever your source code is updated.

Services Used:
GitHub, AWS Elastic Beanstalk, AWS CodeBuild, AWS CodePipeline 

GitHub: GitHub is a version control platform allowing developers to store and manage their code and tracking any changes to it.

AWS Elastic Beanstalk: AWS Elastic Beanstalk, lets you can quickly deploy and manage applications in the AWS Cloud without having to learn about the infrastructure that runs those applications. Elastic Beanstalk reduces management complexity without restricting choice or control. You simply upload your application, and Elastic Beanstalk automatically handles the details of capacity provisioning, load balancing, scaling, and application health monitoring.

AWS CodeBuild: AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy.

AWS CodePipeline: AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates.

Architecture

![Architecture-2](https://user-images.githubusercontent.com/128709137/233804655-48dac75a-57e0-4d97-a0ad-bf2f8448c3f9.PNG)

Section 1: Set up your Github repo
1. To get started fork the source code from here [https://github.com/aws-samples/aws-elastic-beanstalk-express-js-sample]

Section 2: Deploy a web application using AWS Elastic Beanstalk
1. Navigate to AWS Elastic Beanstalk service and choose the orange Create Application button
2. Under application information give a suitable name of your choice
3. Select Node.js from the Platform dropdown menu. This selection should automatically fill in the Platform branch and Platform version menus further down the screen.
4. Under application code, confirm that the radio button next to Sample application is selected
6. Keep all the remaining configuration as default, review the changes and choose create application button
7. After few minutes once you see the green checkmark, you have successfully created an AWS Elastic Beanstalk application and deployed it to an environment.

Section 3: Building the source code stored in GitHub repo


Scetion 4: 

 



