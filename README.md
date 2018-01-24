# STEP 0 :
Opened up port 443 in your EC2 instance Security Group.

# STEP 1 : 
set two enviroment variables "CERTDOMAIN" and "EMAIL" on your Elastic Beanstalk app.

# STEP 2 : 
Create a folder .ebextensions and stick the file "AWS_Single_LetsEncrypt.config" in it (don't forget to change the extension)

# STEP 3 :
Deploy your app and enjoy the green lock ;)
