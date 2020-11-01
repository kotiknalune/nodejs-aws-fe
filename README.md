# Task 2: Serve SPA in AWS

## Results

### Manual deployment

[S3 bucket link](http://rs-aws-app.s3-website-eu-west-1.amazonaws.com/) / [CloudFront link](https://dc5iymr3p5a9f.cloudfront.net/)

### Automated deployment

[S3 bucket link](http://rs-aws-app-auto.s3-website-eu-west-1.amazonaws.com/) / [CloudFront link](https://d1i3djc1goffjb.cloudfront.net/)

## TODO

### 2.1 Manual deployment

- [x] In the AWS Console **create** and **configure** **S3 bucket** to host SPA

- [x] **Build** and **manually upload** the app to the S3 bucket. Check if the app is available

- [x] **Create** a _CloudFront distribution_ . **Check** for S3 bucket policy changes and if the app is available over given CloudFront URL

- [x] **Make** minor but visible changes in the app, **build** and **upload** them to your bucket, and create CloudFront distribution invalidation

### 2.2 Automated deployment (serverless-finch + serverless single-page-app)

- [x]  **Add** and **configure** _serverless_ and _serverless-finch_ plugin. Add necessary npm script(s) to build and deploy your app from your machine in an automated way. **Check** if everything works correctly for you. (_Please note, that after uploading an application's build to the S3 bucket you need to manually create a CloudFront invalidation_)

- [x] **Destroy** created AWS infrastructure (S3 bucket and CloudFront distribution) from the previous part and steps. **Make sure** nothing is left (Will complete after CROSSCHECK)

- [x] **Add** and **configure** _serverless-single-page-app-plugin_ as it is implemented in the demo repository. **Add** necessary npm script(s) to build, upload to your S3 bucket, and invalidate CloudFront cache from your machine in an automated way. Check if everything works fine and all changes appear on the Web. (_Please note, that you don’t need to manually create CloudFront invalidations any more_)
