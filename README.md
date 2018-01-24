.ebextensions script for automatically installing letsencrypt SSL with Webroot mode on an Elastic Beanstalk single instance running Nginx

(!) Based on : https://gist.github.com/tony-gutierrez/198988c34e020af0192bab543d35a62a

# STEP 0 :
Opened up port 443 in your EC2 instance Security Group.

# STEP 1 : 
set two enviroment variables "CERTDOMAIN" and "EMAIL" on your Elastic Beanstalk app.

# STEP 2 : 
Create a folder .ebextensions and stick the file "AWS_Single_LetsEncrypt.config" in it (don't forget to change the extension)

# STEP 3 :
Deploy your app and enjoy the green lock ;)
