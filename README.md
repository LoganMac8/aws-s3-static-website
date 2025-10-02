# AWS S3 Static Website

## 📖 Project Overview
This project demonstrates how to host a static website using **Amazon S3** with public access enabled and static website hosting configured.  

## 🚀 Steps Taken
1. Created an S3 bucket: `logan-s3-static-site-demo` in region `us-west-2`.
2. Disabled “Block all public access” for learning purposes.
3. Uploaded `index.html` with basic HTML content.
4. Enabled **Static Website Hosting** in the S3 bucket properties.
5. Applied a bucket policy to allow public read access.
6. Accessed the live site here:  
   👉 **[Live Website](http://logan-s3-static-site-demo.s3-website-us-west-2.amazonaws.com)**

## 📸 Screenshot
Here’s the deployed site in action:  

![Website Screenshot](Screenshot%202025-10-02%20154548.png)

## 🎯 What I Learned
- Basics of AWS S3 and regions.  
- How to configure S3 buckets for static website hosting.  
- Writing a bucket policy for public read access.  
- Deploying a webpage to the cloud and making it globally accessible.  

## 🔜 Next Steps
- Add **CloudFront CDN** for HTTPS and caching.  
- Secure the bucket with **IAM policies** and Origin Access Control (OAC).  
