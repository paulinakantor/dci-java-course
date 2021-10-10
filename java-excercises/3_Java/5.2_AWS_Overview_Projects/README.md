# Java - Cloud services - AWS Overview - Projects

## Overview
This is introduction to the projects in the AWS Overview submodule.


## Objectives
After making those projects, students should be able to set up their own application that uses database using EC2 instance with database on RDS (PostgreSQL). Also, students should be able to create serverless application using Lambda.


## Materials and Resources
![AWS DOCS](https://docs.aws.amazon.com/)


### Projects - instruction
There are 3 projects.

Students should get an instruction which are steps to go through. After each step students should change each other, so that both students will have a possibility to get their hands dirty with the work.

The main purpose of those projects are to be able to sometimes look for solutions in the internet. AWS have a really good documentation with a lot of code snippets, that may be simply reused.


All AWS related services are meant to be configured via AWS Console (UI).

If students have any troubles with projects, let's share the solution branch with them. Solution branch contains a pdf that is more like tutorial with screen shots that explains exacly "where to click" in order to configure everything in the AWS Console.

Also, on a solution branch, you can find a final Java project that needs to be deployed on EC2/Lambda.

Students have to remember to shut down any launched instances after doing projects (EC2, and especially RDS since there is no free tier anymore).

#### Projects

Spring Boot application with REST endpoint deployed on EC2  
Time: 4TUs ~ 180min   
When: After a lecture about EC2. Students also need to have a knowledge about VPC, Subnets, Security Groups.      
Link: https://github.com/paulinakantor/dci-java-cloud-aws/blob/main/EC2/Setup%20own%20EC2  
Solution: https://github.com/paulinakantor/dci-java-cloud-aws/blob/solutions/EC2/Setup%20own%20EC2%20-%20SOLUTION.pdf
Reference project: https://github.com/paulinakantor/dci-java-cloud-aws/tree/solutions/EC2/awsDemoEC2  


Spring Boot application on EC2 with integration with database on RDS
Time: 3TUs ~ 135min  
When: After students finish the last project, because this one is going to be developed as a continuation. Also, students need to have a knowledge about RDS instances.    
Link: https://github.com/paulinakantor/dci-java-cloud-aws/blob/main/RDS/Set%20up%20RDS%20%2B%20EC2  
Solution: https://github.com/paulinakantor/dci-java-cloud-aws/blob/solutions/RDS/Setup%20RDS%20%2B%20EC2%20-%20SOLUTION.pdf  
Reference project: https://github.com/paulinakantor/dci-java-cloud-aws/tree/solutions/RDS/awsDemoRDS    


AWS Lambda usage example - triggering from S3
Time: 2TUs ~ 90min  
When: After a self study about AWS Lambda  
Link: https://github.com/paulinakantor/dci-java-cloud-aws/blob/main/Lambda/Set%20up%20Lambda%20function  
Solution: https://github.com/paulinakantor/dci-java-cloud-aws/blob/solutions/Lambda/AWS%20Lambda%20-%20SOLUTION.pdf  
Reference project: https://github.com/paulinakantor/dci-java-cloud-aws/tree/solutions/Lambda/awsLambdaDemo    
