Creating a continous delivery pipeline to deploy Sample Node.js App to AWS Elastic Beanstalk

Services Used:
GitHub, AWS Elastic Beanstalk, AWS CodeBuild, AWS CodePipeline 

GitHub: GitHub is a version control platform allowing developers to store and manage their code and tracking any changes to it.

AWS Elastic Beanstalk:
Elastic Beanstalk, lets you can quickly deploy and manage applications in the AWS Cloud without having to learn about the infrastructure that runs those applications. Elastic Beanstalk reduces management complexity without restricting choice or control. You simply upload your application, and Elastic Beanstalk automatically handles the details of capacity provisioning, load balancing, scaling, and application health monitoring.

AWS CodeBuild:

AWS CodePipeline

Architecture
![Architecture-2](https://user-images.githubusercontent.com/128709137/233804655-48dac75a-57e0-4d97-a0ad-bf2f8448c3f9.PNG)

Project Overview: 
-> GitHub is used here as a repository to store the source code
-> AWS Elastic Beanstalk is used to deploy the web application 
-> AWS CodeBuild enables to run the build process of the web app from the GitHub repository
-> AWS CodePipeline helps to setup a continous delivery pipeline with source build and deploy stages. The pipeline will detect code changes in the code GitHub repo          code, build the code using CodeBuild and deploy the changes using CodePipeline to AWS Elastic Beanstalk.
-> A review stage is added to the code pipeline to provide manual approval to this continuous delivery pipeline. Now, the code changes will have to be reviewed and          approved manually before they are deployed to AWS Elastic Beanstalk. 

