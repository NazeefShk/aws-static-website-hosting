# AWS Static Website Hosting

## Project Overview

This project demonstrates the deployment of a static website using Amazon S3. The website is hosted on AWS cloud infrastructure and configured for public access using S3 Static Website Hosting. The project showcases fundamental cloud computing concepts including storage management, access control, website deployment, and cloud-based hosting.

## Technologies Used

* Amazon S3
* HTML5
* CSS3
* AWS Management Console

## Features

* Static website hosting using Amazon S3
* Public website accessibility through S3 website endpoint
* Bucket policy configuration for public access
* Cloud-based content deployment
* Responsive portfolio website

## Architecture

```text
User Browser
      │
      ▼
AWS S3 Website Endpoint
      │
      ▼
Amazon S3 Bucket
 ├── index.html
 └── style.css
```

## Implementation Steps

1. Created an Amazon S3 bucket.
2. Configured bucket settings for static website hosting.
3. Uploaded website files (HTML and CSS).
4. Disabled Block Public Access settings.
5. Configured bucket policies to allow public read access.
6. Enabled Static Website Hosting.
7. Accessed the website through the generated S3 website endpoint.

## Learning Outcomes

* Understanding Amazon S3 storage services.
* Configuring Static Website Hosting in AWS.
* Managing bucket permissions and policies.
* Deploying web applications to cloud infrastructure.
* Implementing basic cloud security and access control concepts.
* Working with AWS cloud management tools.

## Screenshots

### AWS S3 Bucket

Add screenshot here.

### Static Website Hosting Configuration

Add screenshot here.

### Live Website

Add screenshot here.

## Future Enhancements

* Configure a custom domain name.
* Integrate Amazon CloudFront for content delivery.
* Enable HTTPS using AWS services.
* Implement CI/CD deployment using GitHub Actions.
* Add monitoring and logging capabilities.

## Author

**Nazeef Shaikh**

* LinkedIn: https://linkedin.com/in/nazeef10
* GitHub: https://github.com/NazeefShk

## Project Status

Completed ✅
Hosted on Amazon S3 using Static Website Hosting.
