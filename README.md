# Deploying-Static-Website-on-AWS
Hosting a static website that only includes HTML, CSS, and JavaScript files that requires no server-side processing. The whole project has two major intentions to implement:

Hosting a static website on S3 and
Accessing the cached website pages using CloudFront content delivery network (CDN) service.
In this project, I was able to deploy a static website to AWS by performing the following steps:

Created a public S3 bucket and uploaded the website files to my bucket.
Configured the bucket for website hosting and secured it using IAM policies.
Sped up content delivery using AWS’s content distribution network service, CloudFront.
Accessed the website in a browser using the unique CloudFront endpoint.

Prerequisites:
AWS Account
Student-ready starter code - Download and unzip this file.

DEPENDENCIES

Cloud Services:
Amazon Web Services S3 - Resource hosting and deployments
AWS CloudFront - CDN for SPA
AWS EKS - Backend API
AWS DynamoDB - Persistent Datastore
AWS Cognito - User Authentication

Performance Tracking and DevOps Tools:
AWS CloudWatch - Performance and Health checks
Sentry - Bug Reporting
Alternates:
TBD

Google Analytics - Usage Reporting
Alternates:
Mixpanel

Travis (CI/CD)

Frameworks:
Ionic (Javascript) (Frontend)
Node.js (Javascript) (Backend)
