# AWS_IAM

AWS identity and Access Management is used to manage secure access to AWS services and Resources. 

IAM is a feature of AWS account offered at no additional charge, You get charged only for the use of other AWS services by your users.

![AddUsersToGrp](https://github.com/Benn1440/AWS_IAM/assets/67696393/fb5ac169-b641-4e49-a6c8-2106634ae24f)

A collection of users will often need a similar set of permissions. An IAM group can be used to define permissions for multiple users.

When IAM users are added to a group, they inherit all the permissions attached to the group.

A user group can contain many users and a user can belong to multiple user groups.

User groups can be nested they van contain only users, and not nother user groups.

![Group permission](https://github.com/Benn1440/AWS_IAM/assets/67696393/c71a31f4-2f74-45f9-ae98-c61266b26b10)

There is no default user group that automatically includes all users in the AWS account. If you need user groups of that nature, you have to create it and assign each new user to it.

After creating policies a special url is generated so an admin can login, and try accessing and implementing  the policy which has been applied 

https://796341583826.signin.aws.amazon.com/console 

In this instance, we tried deleting an EC2 Instance but got the below error message. 

![RoleApplication](https://github.com/Benn1440/AWS_IAM/assets/67696393/c15b1d18-aa75-4560-b55c-200bfe1e5c37)

# Further Reference to AWS IAM : https://docs.aws.amazon.com/rolesanywhere/latest/userguide/introduction.html






