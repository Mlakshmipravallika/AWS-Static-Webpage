# AWS-Static-Webpage
Hosting Static Webpage on AWS Using Amazon S3 and Route 53

![p1](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/71d52a43-1e71-46f3-885e-2109b2a69418)


Steps to host a static Website in s3 Bucket

1. Sign in to AWS Management Console
2. Create an S3 Buctet
3. Upload Your website Files, Set permissions
4. Enable Static Website Hosting
5. Obtain Your S3 Bucket's Website Endpoint
6. Testing


# Step 1: Sign in to AWS Management Console

Log in to your AWS account or create one if you don't have an AWS account already.

# Step 2: Create an S3 Buctet

1. Go to the AWS S3 console.
2. Click on the "Create bucket" button.
3. Enter a unique and globally-unique bucket name (e.g., "my-static-website").
4. Choose the region where you want to create the bucket.
5.If you want your bucket to be publicly accessible, you can adjust these settings or you can leave them and adjust later
6. Enable Bucket versioning to keep multiple versions of objects in the bucket.This can help with data recovery and compliance.
7. Give tags to track your bucket
8. Leave remainig settings as it is and click on create Bucket.
9. You'll receive a confirmation message, and the new bucket will appear in the list of buckets in your S3 dashboard.

![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/5b68fc59-b390-487b-8a34-0bf11503ce8d)
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/9a346c50-e122-4c2c-b4a8-e730f62b8945)
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/b0a2054e-8591-4ecf-b7ba-a753d631fa89)
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/a6471f3e-bd6f-4620-aef9-3559bdbf1e3a)
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/c4e9a203-7e49-4fef-98cf-381bbd32de2d)

# Step 3: Upload your Website Files and Set Permissions

1. In the S3 bucket, navigate to the "Objects" tab.
2. Click the "Upload" button to upload your static website files
3. Grant public access and access to other AWS accounts.
4. Finally review and click on upload Button
   
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/b54ed426-bf9f-4b8c-a940-ed3ce64886d7)
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/6fc69562-f6bd-4aae-81f6-b0771a7e266f)

# Step 4: Enable Static Website Hosting

1. Select the newly created S3 bucket from the S3 console.
2. In the bucket properties, navigate to the "Static website hosting" section.
3. Choose "Use this bucket to host a website."
4. Enter the index document (e.g., "index.html") and error document (optional, e.g., "error.html") if you have one.
5. Click "Save."

![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/3b8cd98e-6e9e-43f8-8b17-d72f12dbf899)
![image](https://github.com/Mlakshmipravallika/AWS-Static-Webpage/assets/89599922/3b8d57f9-b64f-4458-8253-fbe3ed58dce0)

# Step 5: Obtain Your S3 Bucket's Website Endpoint:

1. Select your S3 bucket that hosts your static website.
2. In the bucket properties, go to the "Static website hosting" section.
3. You'll see an endpoint URL like this: http://your-bucket-name.s3-website-your-region.amazonaws.com/ or http://your-bucket-name.s3.amazonaws.com/ (if you didn't enable website hosting).
4. Copy this URL and use it or you can provide custome domine by using aws famous service like Route 53 (which is chargable)

# Step 6: Testing:

1. With in few minutes you can be able to access your static website using your custom domain or the S3 bucket's endpoint URL.
2. Send this URL to your friend try to access your website <h2> !!!!! WOW !!! </h2>

3. I hosted my portfolio webpage in s3 you can refer webpage code above but remember one thing s3 free tier can give only 2000 requests for free if you reach above limit then s3 going to charge u.










