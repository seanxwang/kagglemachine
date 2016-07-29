# kagglemachine
“data science server in a box” with current open source toolkit (RStudio, Jupyter Notebook, Anaconda, Xgboost…). Builds automatically, fully configured ready for use in less than five minutes.

##What it is:
An AWS AMI which provides “data science server in a box” with current open source toolkit (RStudio, Jupyter Notebook, Anaconda, Xgboost…). Builds automatically, fully configured ready for use in less than five minutes.

##How to build kaggle machine
Use the CloudFormation template to launch your Kaggle Machine.
Download the template, launch stack by selecting instance type and using your existing key pair.
Note the AMIs are currently available in us-east-1 and us-west-2. For other regions, you can build your machine in the above two regions, and copy AMI across regions.

![Kaggle Machine Stack](/kagglestack.png?raw=true "Kaggle Machine Stack")

##How to use Kaggle machine
To use Kaggle Machine for your data science projects, please refer to:
http://www.seanxwang.com/2016/06/aws-kaggle-machine-turnkey-data-science.html
