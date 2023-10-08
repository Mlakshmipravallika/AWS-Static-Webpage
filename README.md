# AWS-Static-Webpage
Hosting Static Webpage on AWS Using Amazon S3 and Route 53

Steps to host a static Website in s3 Bucket

1. Sign in to AWS Management Console
2. Create an S3 Buctet
3. Upload Your website Files
4. Set permissions
5. Enable Static Website Hosting
6. DNS Configuration
7. Testing


# Step 1: Sign in to AWS Management Console

Log in to your AWS account or create one if you don't have an AWS account already.

# Step 2: Create an S3 Buctet

1. Go to the AWS S3 console.
2. Click on the "Create bucket" button.
3. Enter a unique and globally-unique bucket name (e.g., "my-static-website").
4. Choose the region where you want to create the bucket.
   
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/5b68fc59-b390-487b-8a34-0bf11503ce8d)

<h3>set permissions to Bucket and Objects</h3>
5.If you want your bucket to be publicly accessible, you can adjust these settings or you can leave them and adjust later

![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/9a346c50-e122-4c2c-b4a8-e730f62b8945)
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/b0a2054e-8591-4ecf-b7ba-a753d631fa89)

<h3>Bucket Versioning</h3>
6. Enable Bucket versioning to keep multiple versions of objects in the bucket.
   This can help with data recovery and compliance.

7. Give tags to track your bucket

![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/a6471f3e-bd6f-4620-aef9-3559bdbf1e3a)

8. Leave remainig settings as it is and click on create Bucket.

![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/c4e9a203-7e49-4fef-98cf-381bbd32de2d)





