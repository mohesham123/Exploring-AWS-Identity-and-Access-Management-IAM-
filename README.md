# Exploring-AWS-Identity-and-Access-Management-IAM-
# Project 6: Exploring AWS Identity and Access Management (IAM)

## Lab Overview  
This project involves exploring AWS Identity and Access Management (IAM) by managing users, groups, and policies within AWS. The objective is to understand how permissions are assigned and managed through IAM, enabling users to perform specific tasks based on their roles.

---

## Learning Objectives  
By completing this lab, you will:  
- Explore and understand pre-created IAM users and groups.  
- Inspect IAM policies attached to groups and understand their structure.  
- Add users to groups and verify the inherited permissions.  
- Test the effects of policies on user permissions in AWS services.  
- Use AWS CLI to manage IAM roles and policies.  

---

## Requirements  
- **Tools**:  
  - AWS Management Console  
  - AWS CLI (Command Line Interface)  

- **Lab Environment Setup**:  
  1. Access the AWS Management Console with provided credentials.  
  2. Ensure AWS CLI is installed on your system. Refer to the [AWS CLI installation guide](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) if needed.  

---

## Tasks  

### Task 1: Explore Users and Groups  
1. Log in to the AWS Management Console and navigate to IAM.  
2. List and explore pre-created IAM users and groups.  
3. Inspect the details and permissions associated with each user.  

### Task 2: Inspect IAM Policies  
1. Explore the policies attached to the user groups.  
2. Understand the JSON structure of IAM policies, focusing on:  
   - **Effect**  
   - **Action**  
   - **Resource**  

### Task 3: Add Users to Groups  
1. Add specific users to groups using AWS CLI or Console:  
   - **User-1**: Add to **S3-Support** (Read-only access to S3).  
   - **User-2**: Add to **EC2-Support** (Read-only access to EC2).  
   - **User-3**: Add to **EC2-Admin** (View, Start, and Stop EC2 instances).  

### Task 4: Test Permissions  
1. Sign in as each user in a private browser session using the IAM sign-in URL.  
2. Test permissions based on group policies:  
   - Check S3 access for **User-1**.  
   - Verify EC2 read-only access for **User-2**.  
   - Validate EC2 admin capabilities for **User-3**.  

---

## Lab Submission  

### Verification  
1. Test permissions and document the results for each task.  

### Submission  
1. Capture screenshots of successful task completion.  
2. Provide a summary of your learnings.  
3. Submit all commands used in a `.sh` file.  

---

## Important Notes  
- Ensure you are working in the correct AWS region specified for the lab.  
- Note any errors caused by limited permissions in the lab environment. These errors will not affect task completion.  

---

## Additional Resources  
- [AWS IAM Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)  
- [AWS CLI User Guide](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)  

---

## Grading Criteria  
- Proper execution of all tasks.  
- Accurate testing of permissions.  
- Clear and concise documentation of steps and learnings.  
