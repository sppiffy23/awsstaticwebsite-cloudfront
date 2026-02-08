# awsstaticwebsite-cloudfront




i created an s3 bucket using my aws free-tier account 
i then enabled it for static website hosting 
under permissions , i was able to set a bucket policy but i came accross an error  which required me to edit my public access TO 

"AWS enforces Block Public Access to prevent accidental data leaks.
 Even admins cannot override it unless they explicitly disable it"

N.B-“S3 Block Public Access overrides bucket policies to prevent unintended public exposure.”

i was then able to update my bucket policy and save it successfully.
heading straight to cloudfront ,i launced it and created distribution 
