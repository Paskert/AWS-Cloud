# AWS-Cloud
#### Cloud computing is on demand delivery of computing power, database, storage, applications.
#### via the internet on pay-as-you-go bases.

### There are different types of cloud :- 
#### Public Cloud
#### Private Cloud
#### Hybrid Cloud


------------------------------------------- DAY 2 ------------------------------------------------

How do you pay for AWS?

    pay for what you use
    pay less when you reserve
    pay less when you use more and as AWS grows

Services 

    Amazon VPC
    Elastic Beanstalk
    Auto Scaling
    AWS cloudFormation
    AWS Identity and Access Management (IAM)

Take aways

    There is no charge (with sorne exceptions) for.
    Inbound data transfer.
    
    • Data transfer between services within the same AWS Region.
    • Pay for what you use.
    • Start and stop anytime.
      No long-term contracts are required.
    • Some services are free, but the other AWS services that they provision might not be free

SCP(service control policy) :- document or policy which well tell an organization can or cannot do

Key Features and benefits
    
    Policy-based account management
    
    Group based account management
    
    Application programming interfaces (APIs) that automate account management
    
    Consolidated billing

Security with AWS Organizaations

Control access with AWS Identitiy and Access Management

SCPs enable you to allow or deny access to AWS services for individuals or group accounts in an organizational unit (OU)

Amazon EC2 Pricing
    
    On-Demand :- Start & stop wehn needed instantly
    Spot :- Flexible allocation when avaliable on spot
    Reserved :- committed for 1 to 3 years
    Compute Saving Plan :- saving upto 66% on compute usage

Amazon EC2 Dedicated computing
    
    Dedicated instance
    Dedicated host - most expensive
    higher cost
    suitable for complicance
    reduction in cost by resercved instance

Auto Scaling

### Elastic Load Balancing

Unbalanced

Balanced

Load Balancer Types :-
HTTP


### PUB/SUB Messaging model

SQS :- Simple queuing servive 

SNS :- Simple notification service

### AWS Lambda

I don't have to manage my code,take my code and deploy it in lambda

it is called as Serverless compute service

------------------------------------------- DAY 4 ------------------------------------------------

VPCs and subnets

VPCS:

• Logically isolated from other VPCS

• Dedicated to your AWS account

• Belong to a single AWS Region and can span multiple Availability Zones

Subnets:

• Range of ip addresses that divide a VPC

• Belong to a single Availability Zone

• Classified as public or private



You can connect VPCs in your own AWS.account, between AW's accounts, or between AWS Regions

Restrictions:

IP spaces cannot overlap.

Transitive peering is not supported.

You can only have one peering resource between the same two VPCS


### AWS Direct Connect

aws direct connect is a service which would provide secure connection from the customer to the cloud

### Security groups (2 of 2)

    they act at instance level
    Security groups have rules that control inbound and outbound instance traffic
    Default security groups deny all inbound traffic and allow all cutbound traffic    
    Security groups are stateful.

### Network access control list
    Network access control lists (network ACLS 2 of 2)
    A network ACL has separate inbound and outbound rules, and each rule can either allow or deny traffic 
    Default network ACLS allow all inbound and outbound IPv4 traffic 
    Network ACLs are stateless.

### Custom network ACLS examples
    
    Custom network ACLs deny all inbound and outbound traffic until you add rules. 
    You can specify both allow and deny rules.
    Rules are evaluated in number order, starting with the lowest number
