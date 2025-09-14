# Lab 1: Logging with CloudTrail

## What I Did
- Created a new CloudTrail trail (`SecurityPlusTrail`) that applies to all regions.
- Sent logs to an S3 bucket (`securityplus-trail-123456`).
- Verified that events were captured in Event History.

## What I Saw
Example events:
- CreateTrail (cloudtrail.amazonaws.com)
- StartLogging (cloudtrail.amazonaws.com)
- PutBucketEncryption (s3.amazonaws.com)
- CreateBucket (s3.amazonaws.com)

## Why This Matters (Security+ Tie-In)
- This is **audit logging** → proves accountability (non-repudiation).
- Maps to Security+ objectives around **monitoring, logging, and detection**.
- In an incident, I can go back and see exactly what actions were taken and by whom.

## Screenshot
![CloudTrail Event History](images/cloudtrail-event.png)
