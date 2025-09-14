# Lab 2: IAM Least Privilege

## What I Did
- Created a new IAM user called `SecPlusTestUser`.
- Attached only the `AmazonS3ReadOnlyAccess` policy.

## What I Saw
- User could view S3 buckets.
- User could NOT create or delete buckets (got Access Denied).

## Why This Matters (Security+ Tie-In)
- Demonstrates the **Principle of Least Privilege**.
- If an attacker steals this account, they can only see buckets — not destroy or change them.
- Ties to Security+ concepts of **Access Control** and **Defense in Depth**.

## Screenshot
![IAM User Permissions](images/iam-least-privilege.png)

