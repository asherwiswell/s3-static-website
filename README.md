# s3-static-website


## Project Title

AWS S3 Static Website Hosting


## Objective

This project demonstrates how to host a static website using Amazon S3. 
The project includes creating an S3 bucket, uploading website files, configuring a bucket policy for public access, and enabling static website hosting.

## Architecture

The project uses the following AWS services:

- Amazon S3
- Bucket Policy for public access
- Static website hosting

## Technologies Used

- Amazon S3
- HTML
- AWS Management Console

## Deployment Steps

1. Created an S3 bucket with a globally unique name.
2. Disabled block public access to allow website hosting.
3. Uploaded the `index.html` file to the bucket.
4. Enabled static website hosting in the bucket properties.
5. Added a bucket policy to allow public read access.
6. Accessed the website through the S3 website endpoint.

## Screenshots

### S3 Bucket Created
![S3 Bucket](create-bucke.png)

### Static Website Hosting Enabled
![Website Hosting](bucket-poliy.png)

### Uploading files
![Uploading files](upload-fies.png)

### Website in browser
![Website Live](websie.png)
