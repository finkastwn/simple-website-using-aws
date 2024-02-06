How to deploy this website to AWS Management Console.

1. Clone this repository
   ```git clone https://github.com/finkastwn/simple-website-using-aws.git```
2. Create Bucket S3
   - Open AWS Management Console.
   - Go to S3
   - Click 'Create Bucket'
   - Add your bucket name
   - Click 'Create Bucket' button
3. Upload html file
   - Open your existing bucket
   - Click 'Upload' button
   - Upload ```index.html``` file
   - Click 'Next' until you see 'Upload' button
   - Click 'Upload' button
4. Make ```index.html``` as public
   - Click ```index.html```
   - Click 'Actions' and 'Make Public'
5. Access your website
   - At properties tab, you can see 'Object URL'
   - ```https://${bucket-name}.s3.ap-southeast-1.amazonaws.com/index.html```
