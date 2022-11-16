# AWS Overview and MFA Setup

### What is cloud?

Back in the old days,organizations and other companies use to host and maintain hardware which includes computing,storage and networking equipment in their own data centre. It asks for a whole separate division to do its maintainance and management which was costly and very uneconomical.
    
   In order to resolve such issues, the concept of the cloud computing emerged. It is an on-demand services for the IT resources with concept of pay-as-you-go pricing. One dont have to manage or own the data centres, everything can be done in the virtualized environment and service over the internet.
   
 ### Overview of the benefits:
 
  - Pay as you go
  - Massive economies of scale.
  - Scale the infrastructure as per need.
  - Increase speed and agility
  - No maintainance cost for the data centre
  - Go global in minutes
  
  
  ### AWS region selection
  
  Consider four main aspects when deciding the AWS region. 
  
  - Latency
  - Price
  - Service availability
  - Data compliance
        
  ### Interacting with AWS
   
There are 3 ways that you can interact with AWS:

- AWS Management Console
- AWS Command Line Interface (CLI)
- AWS Software Development Kits (SDKs)

 ### Security and AWS shared Responsibility model
        
   - What is the AWS and Customer Responsible for?
        
   Infrastructure: 
   
        Consists - Compute services, Amazon EC2
        AWS role - Manages the infrastructure and foundation services.
        Customer role - Manages Operating system, application platform, encryption,protecting, customer's data.
      
   Container services:
   
        Consists - Amazon RDS
        AWS Role - Manages infrastructure and foundation services, operating system,and application platform. 
        Customer role - Manages customer data,encryption of that data,protecting it through network firewalls and backups.
                
        
   Abstracted services:
    
        Consists - Amazon S3
        AWS Role - Manages infrastructure layer, Operating systems,platforms,service-side encryption and data protection.
        Customer role - Manages customer data, protecting it by client side encryption.
        
        
        
        
    
 
          
 Note: From this step forward you will need AWS already set up, the guidelines to create an account would be on [AWS Signup Guide](https://docs.aws.amazon.com/accounts/latest/reference/manage-acct-creating.html)
          
          

