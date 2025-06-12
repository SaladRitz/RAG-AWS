# RAG-AWS
An end to end Advanced Rag application using Langchain and AWS


For using Different AWS Bedrock models refer to the API details from the repo below:
https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/python/example_code/bedrock-runtime/models

# Configuring AWS
Go to AWS IAM -> Users -> Select User -> Create Access Key -> Copy your AWS Access Key ID and AWS Secret Access Key and download the .csv file for future use of that particular access key instance.

In your vs code CLI, create a venv using command: conda create -p venv python==3.10

Activate venv: conda activate venv/

Now configure AWS in CLI: aws configure

AWS Access Key ID [None]: {Enter your AWS Access Key ID}

AWS Secret Access Key [None]: {Enter your AWS Secret Access Key}

Default region name [None]: {Enter the region that you are operating on AWS} eg: us-east-1

Default output format [None]: json

# Install Packages
In your CLI type pip install -r requirements.txt after activating your conda venv.
