# CLOUD-SECURITY-IMPLEMENTATION

COMPANY: CODETECH IT SOLUTIONS

NAME: PRIYADHARSHINI B L

INTERN ID: CT04DF413

DOMAIN: CLOUD COMPUTING

DURATIONS: 4 WEEKS

MENTOR: NEELA SANTHOSH

# TASK DESCRIPTION: CLOUD-SECURITY-IMPLEMENTATION

# Internship Task 4 – Cloud Security Implementation

Platform Used: Google Cloud
Lab Reference: Getting Started with Cloud KMS and Cloud IAM Quickstart

*As part of my internship's fourth task, I worked on implementing security features using Google Cloud. The task focused on three major areas: IAM policies, secure storage, and data encryption. I chose to complete this task using Google Cloud services, which provided me with the required tools and settings to apply strong security measures. To help me understand the concepts clearly, I referred to the lab titled "Getting Started with Cloud KMS and Cloud IAM Quickstart" from the Google Cloud Skill Boost platform.*

*Step 1*: Understanding IAM (Identity and Access Management)
IAM is one of the most important features in cloud security. It helps control who can access what resources and what actions they can perform. In this step, I learned how to create roles and give permissions to users and service accounts. Using the Google Cloud Console, I explored how to assign roles such as "Viewer", "Editor", and "Owner" to different members.

To implement this in my project, I created a new IAM role and assigned it to a test user. I used the "Principle of Least Privilege", which means I gave only the permissions that were necessary and nothing more. This helps reduce the risk of unauthorized access. I also learned to remove or edit IAM policies, which is important for managing security on a regular basis.

*Step 2*: Secure Storage Using Cloud Storage
The next part of the task was to make sure that the data stored in the cloud was secure. I used Google Cloud Storage for this. I created a bucket and set permissions on it. I avoided making the bucket public, and instead gave access only to specific users using IAM roles.

Inside the bucket, I uploaded a test file. I ensured that the bucket was private and could only be accessed by the roles that were assigned in IAM. This helped in applying secure storage best practices. I also explored bucket-level and object-level permissions to understand how to protect files in a more detailed way.

*Step 3*: Data Encryption with Cloud KMS
Encryption is the third and final part of the task. Google Cloud by default encrypts all data, but for stronger control, I used Cloud KMS (Key Management Service) to create my own encryption key.

In the lab, I followed the steps to:

Create a key ring and a symmetric encryption key

Assign permissions to use the key

Apply the key to a Cloud Storage bucket for customer-managed encryption

I learned that with KMS, we can manage and rotate keys manually, which gives better control and security. After assigning the KMS key to my bucket, I tested it by uploading a new file and verifying that it used the KMS key for encryption.

#Final Setup and Output

At the end of this task, I had:

IAM roles properly configured to allow only the required access

A private storage bucket with secured access

A working encryption setup using Cloud KMS

I took screenshots of the IAM roles, storage bucket settings, and KMS configuration to include in my report and GitHub repository. These show that the security features were properly set up.

#Conclusion

This task helped me understand the importance of cloud security and how to implement it using IAM, secure storage, and encryption. By using the hands-on lab, I was able to apply the concepts practically, which made learning easier. This experience will definitely help me in real-world cloud projects in the future.

#OUTPUT

final-kms-keyring-output.png

![Image](https://github.com/user-attachments/assets/1ad439e0-a4e8-43c7-9ba0-5bad6fbc6332)

