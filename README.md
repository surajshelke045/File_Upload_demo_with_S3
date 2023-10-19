# File_Upload_demo_with_S3
This application is built using Spring Boot, MySQL, and AWS S3. It enables users to upload files of any type to an AWS S3 bucket, download files from the S3 bucket, and delete files stored in the S3 bucket.

# TO RUN THIS APP FOLLOW BELOW STEPS :-

STEP 1:- clone this repository in your system.

STEP 2:- create S3 bucket on AWS 

STEP 3:- update application.yml file as per your AWS ACCESS-KEY,SECRET-KEY,YOUR-BUCKET-NAME

STEP 4:- go to POSTMAN and test this APIs

# for upload file :-
# POST
http://localhost:9090/file/upload

# for download file :-
# GET
http://localhost:9090/file/download/{fileName}

here you need to specify file name instead of {fileName} 

# for delete file :-
# DELETE
http://localhost:9090/file/delete/{fileName}

here you need to specify file name instead of {fileName} 

