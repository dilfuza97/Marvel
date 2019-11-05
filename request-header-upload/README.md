How to use the script?

Before using the script you will need to set up your environment variables. You can put your environment variables inside ~/.bashr or just run export command to set environment variable for current session

export ACCESS_KEY="Your AWS Access Key"
export SECRET_KEY="Your AWS Secret Key"
After you set your environment variables you will need to install some libraries to run script.

pip install -r requirements.txt
After you have installed all libraries your are ready to run the script

python request-header-upload/upload-header.py
