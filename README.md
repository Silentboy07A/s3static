
 S3 Static Website Hosting using LocalStack

 Overview

This project demonstrates how to host a static website using Amazon S3 concepts in a local development environment with LocalStack.

The project includes creating an S3 bucket, uploading website files, enabling static website hosting, and configuring public access using a bucket policy.

 Technologies Used

* AWS CLI
* LocalStack
* Amazon S3
* HTML
* JSON

 Project Architecture

Local HTML File → S3 Bucket → Static Website Hosting → Public Access Policy

 Steps Performed

 1. Created an S3 Bucket

Created a bucket named `sakthi-bucket`.

 2. Uploaded Website Files

Uploaded `index.html` to the bucket using AWS CLI.
3. Enabled Static Website Hosting

Configured the bucket to use `index.html` as the default page.

4. Configured Bucket Policy

Created a public read policy to allow access to website content.

 Files

* `index.html` – Website page
* `website.json` – Static website hosting configuration
* `policy.json` – Bucket access policy

Concepts Learned

* Amazon S3 Buckets
* S3 Objects
* Static Website Hosting
* Bucket Policies
* Public Access Management
* AWS CLI Operations

  ## Screenshots

### Bucket Created
![Bucket Created](Screenshot%202026-06-13%2017281....png)

### File Uploaded
![File Uploaded](Screenshot%202026-06-13%2017283....png)

### Website Hosting Configuration
![Website Hosting](Screenshot%202026-06-13%2017284....png)

### Bucket Policy
![Bucket Policy](Screenshot%202026-06-13%2017290....png)

 Author

Sakthi B

