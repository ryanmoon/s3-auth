# S3-Auth

## Description

S3-Auth allows munki clients to connect securely, and directly to a munki repo hosted in [S3](https://aws.amazon.com/s3).

## Instructions for Use
  - Place middleware_s3.py into `/usr/local/munki`
  - `sudo defaults write /Library/Preferences/com.github.ryanmoon.s3-auth AccessKey 'AKIAIX2QPWZ7EXAMPLE'`

  - `sudo defaults write /Library/Preferences/com.github.ryanmoon.s3-auth SecretKey 'z5MFJCcEyYBmh2BxbrlZBWNJ4izEXAMPLE'`

  - `sudo defaults write /Library/Preferences/com.github.ryanmoon.s3-auth Region 'us-west-2'`
  - `sudo defaults write /Library/Preferences/ManagedInstalls SoftwareRepoURL  "https://S3_BUCKET_GOES_HERE.s3.amazonaws.com"`
