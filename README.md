# Exploring-AWS-Identity-and-Access-Management-IAM-
Project 6: Exploring AWS Identity and Access Management (IAM)
Lab Overview
In this lab, you will explore AWS Identity and Access Management (IAM) by managing users, groups, and policies within AWS. The objective is to understand how permissions are assigned and managed through IAM, allowing users to perform specific tasks based on their roles.
Learning Objectives
By the end of this lab, students will be able to:
 Explore and understand pre-created IAM users and groups.
 Inspect IAM policies attached to groups and understand their structure.
 Add users to groups and verify the inherited permissions.
 Test the effects of policies on user permissions in AWS services.
 Use AWS CLI to manage IAM roles and policies.
Requirements
 Tools: AWS Management Console, AWS CLI (Command Line Interface)
Lab Environment Setup
1. Access AWS Console: Ensure that you can access the AWS Management Console with the provided credentials.
2. AWS CLI Installation: Make sure AWS CLI is installed on your system. If not, refer to the AWS CLI installation guide.
Tasks to Complete
Task 1: Explore Users and Groups
 Log in to the AWS Management Console and navigate to IAM.
 List and explore pre-created IAM users and groups.
 Inspect the details and permissions associated with each user.
Task 2: Inspect IAM Policies
 Explore the policies attached to the user groups.
 Understand the JSON structure of IAM policies, including statements like Effect, Action, and Resource.
Task 3: Add Users to Groups
 Use AWS CLI or Console to add specific users to groups according to their roles:
o User-1 to S3-Support (Read-only access to S3).
o User-2 to EC2-Support (Read-only access to EC2).
o User-3 to EC2-Admin (View, Start, and Stop EC2 instances).
Task 4: Test Permissions
 Sign in as each user in a private browser session using the IAM sign-in URL.
 Test access to AWS services according to group policies:
o Check S3 access for user-1.
o Check EC2 read-only access for user-2.
o Verify EC2 admin capabilities for user-3.
Lab Submission
 Verification: After completing each task, ensure to test permissions and document the results.
 Submit: Capture screenshots of your console showing each step's successful completion. Submit these screenshots along with a summary of what you learned.
 Commands: All the commands you have used in “.sh” file
Important Notes
 Ensure you are working in the correct AWS region as specified at the beginning of the lab.
 Errors due to limited permissions in the lab environment should be noted but do not affect the overall completion of tasks.
Additional Resources
 AWS IAM Documentation: Link
 AWS CLI User Guide: Link
Grading Criteria
 Proper execution of each task.
 Accurate testing of permissions.
 Clear and concise documentation of the steps and learnings.
