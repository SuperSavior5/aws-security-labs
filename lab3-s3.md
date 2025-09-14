# Lab 3: S3 Hardening

## What I Did
- Created a new S3 bucket with "Block Public Access" turned on.
- Enabled default encryption (SSE-S3).
- Uploaded a test file (`hello.txt`).
- Verified encryption worked and that public access was blocked.

## What I Saw
- Bucket permissions showed Block Public Access = On.
- File properties showed "Encryption: AES-256".
- Attempt to make file public failed.

## Why This Matters (Security+ Tie-In)
- Protects data at rest using **encryption**.
- Prevents **data leakage** by blocking public access.
- Demonstrates **Defense in Depth**: even if a user tries to misconfigure, AWS blocks it.

## Screenshot
## Screenshot
## Screenshots
![S3 Block Public Access](images/s3-block-public.png)
![S3 File Encryption](images/s3-encryption.png)

