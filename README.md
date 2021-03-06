<img src="https://yesteacher.app/img/yesteacher.png" width="50%"/>

>  # Back-end BoilerPlate From  <a href="https://yesteacher.app">YesTeacher.App</a>

##### Following dependencies are mentioned in the [requirements.txt](requirements.txt) file
**pip3** should be installed to install all the dependencies

`sudo apt install python3-pip`

`pip3 install -r requirements.txt`

`python3 application.py` will create a server on port <b>5002</b>

# Deployment

**application deployment environments**

`export APPLICATION_NAME='yourapplicationname'`

`export APPLICATION_ENVIRONMENT='yourapplication-env'`

Look into s3 bucket it will have name with below based on your region
`export S3_BUCKET='elasticbeanstalk-us-east-1-example'`

`export aws_access_key_id='**************'`
And
`export aws_secret_access_key='*************'`

For Pushing updates to Elastic Beanstalk Check [deployment.py](deployment.py) 
Run [deployment.py](deployment.py) As Main Module


With Deployment Configuration Elastic BeanStalk Production Ready Check 
[.ebextensions](.ebextensions) Folder



# Linking Multiple Repo
**You will need multiple repository to be linked at some time,So when you will, Use this**

Define a git remote which will point to multiple git remotes.

Say, we call it **multiple**: `git remote add multiple REMOTE-URL-1`.

Register 1st push URL: `git remote set-url --add --push multiple REMOTE-URL-1`.
Register 2nd push URL: `git remote set-url --add --push multiple REMOTE-URL-2`.

Push a branch to all the remotes with `git push multiple origin`


# Supported WebServer And WebSocket

**With Cross Origin Request CORS Added**  [application.py](application.py)

# All reditects at one place [redirect_url.py](redirect_url.py)


# Some Common Requirements
<b>
<ol>
<li>boto3</li>
<li>requests</li>
<li>mysql-connector</li>
<li>pytz</li>
<li>pywebpush</li>
<li>Pillow</li>
</ol>
</b>
