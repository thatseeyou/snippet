# AWS scripts

## Limited permissions to students
To give restricted permissions to access AWS APIs using AWS IAM and CLI. Bash scripts are provided to students not familiar with AWS CLI. 

These scripts was used for practicing Apache Hadoop.

### Prerequisites
* Install AWS CLI
    - [Installing the AWS Command Line Interface](http://docs.aws.amazon.com/cli/latest/userguide/installing.html)

* Create access key for student with limited permission
    - [AWS console for IAM](https://console.aws.amazon.com/iam/home?#users)

* AWS CLI configure
    - $ aws configure

### BASH scripts 
* ec2-list
    - Show selective attributes for EC2 instances

* ec2-start
    - Start EC2 instance

* ec2-stop
    - Stop EC2 instance

* ec2-student
    - Start/Stop EC2 instances allocated to specific student.
    - EC2 custom tag 'student' must be set.
