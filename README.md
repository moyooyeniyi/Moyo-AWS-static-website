# AWS Static Website

## Project Overview

This is my first AWS cloud project.

The goal is to build and host a static website using AWS S3.

## Technologies

- HTML
- CSS
- Git
- GitHub
- AWS S3

## Progress


## Step 1: Created Website Files

This is the first version of my website running locally.

![Local Website](images/01-local-website.png)



## Step 2: Created S3 Bucket

I created an Amazon S3 bucket that will host my static website.

![S3 Bucket Created](images/02-s3-bucket-created.png)




## Step 3: Enabled Static Website Hosting

I enabled static website hosting on my S3 bucket and configured index.html as the landing page.

![Static Website Hosting](images/03-static-hosting-enabled.png)


## Step 4: Uploaded Website Files to S3

I uploaded my website files (index.html and style.css) to my Amazon S3 bucket.

These files will be used to host the static website.

![Files Uploaded](images/04-files-uploaded.png)


## Step 5: Enabled Public Access

To make the website accessible from the internet, I updated the S3 bucket permissions and disabled Block Public Access settings.

This allows visitors to access the website files stored in the bucket.

![Public Access Enabled](images/05-public-access-enabled.png)


## Step 6: Added Bucket Policy

I configured a bucket policy to allow public read access to the objects stored in my Amazon S3 bucket.

This policy allows visitors to access the website files through the S3 website endpoint.

![Bucket Policy Added](images/06-bucket-policy-added.png)

## Step 7: Website Live on AWS

After configuring static website hosting, public access settings, and the bucket policy, I successfully hosted my website on AWS S3.

The website is now publicly accessible through the S3 website endpoint.

![Website Live on AWS](images/07-website-live1.png)



## Step 8: Created CloudFront Distribution

I created an Amazon CloudFront distribution and connected it to my S3 bucket.

CloudFront acts as a Content Delivery Network (CDN), helping improve performance and providing a more production-ready architecture.

![CloudFront Distribution](images/09-cloudfront-distribution-created.png)

## Step 9: Website Delivered Through CloudFront

After the CloudFront distribution finished deploying, I successfully accessed my website through the CloudFront domain.

This setup improves website performance and follows AWS best practices for static website delivery.

![CloudFront Website Live](images/10-cloudfront-website-live.png)