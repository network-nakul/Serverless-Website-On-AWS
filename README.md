# Serverless-Website-On-AWS

This project demonstrates hosting a static website on AWS using serverless architecture. The setup includes **Amazon S3** for static website hosting and **CloudFront** for global content delivery, providing scalability and high performance.

## Project Overview

This project was completed as part of my internship at EliteTech Intern. It focuses on deploying a static website without a traditional server, leveraging AWS services for efficient and cost-effective hosting.

## Tech Stack

- **Amazon S3**: Used for static website hosting and storing HTML/CSS files.
- **AWS CloudFront**: Configured as a Content Delivery Network (CDN) to optimize loading times and provide global access.

## Key Steps

1. **Setup Amazon S3**: 
   - Created an S3 bucket and uploaded HTML/CSS files.
   - Enabled **Static Website Hosting** for direct site access via S3.

2. **Testing S3 Website**: 
   - Verified the website was live and accessible through the S3-generated URL.

3. **Configure CloudFront**:
   - Set up a CloudFront distribution linked to the S3 bucket.
   - Enabled global content delivery to enhance performance and accessibility.

4. **Final Verification**: 
   - Tested the CloudFront URL to confirm the website's functionality and performance.

## Usage

To access the website:
- Visit the **CloudFront distribution URL** for the live version of the site.

## Lessons Learned

- Gained practical experience with AWS serverless infrastructure.
- Enhanced skills in configuring S3 and CloudFront for web hosting and content delivery.

## Future Improvements

- Adding backend functionality using AWS Lambda and API Gateway.
- Implementing HTTPS and custom domain support.


