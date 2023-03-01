# API-Data-Exploration-and-Analysis-

#Install required packages

1. pip install requests
2. pip install beautifulsoup4
3. pip install pandas

#script.py file

To upload .csv file into S3 bucket, replace "your_aws_bucket_name" in script.py file with your S3 bucket name

#keys.py file

* To access the S3 bucket and upload files into it, we have to give the credentials(access_key, secret_access_key) of S3 bucket.
* To find access_key and secret_access_key go to security credentials -> access keys -> create access key - > Agree to the policies -> Copy Access Key and Secret Access Key and replace with the *** in keys.py file. 


