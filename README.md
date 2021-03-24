# Creating Access Keys

Create max of 2 Access Keys for each Identity \
Secret Access Key is only showed to you by AWS when creating the Access Key, and that's it! You're responsible for holding onto this info. \
You can Delete Access Keys, or Make Inactive.

Account dropdown → My Security Credentials \
Scroll down to "Access Keys for CLI, SDK, & API access" → Create Access Key \
Access Key ID (Public, like a username) & Secret Access Key (Private, like a password) \
Download iamadmin_accessKeys.csv file \
Rename: iamadmin_accessKeys_general.csv

\
**Install AWS CLI v2:** \
https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-windows.html \
Topics → click "Install or update the AWS CLI version 2 on Windows using the MSI installer" \
For the latest version of the AWS CLI: clicking this link will start a download \
Accept all the defaults in this installation \
Open Command Prompt \
run the command "aws" (you should see usage instructions, then everything installed successfully as expected) \
aws --version (this should return aws-cli/2.X.XX indicating version 2)

\
**Configuring the Command Line Interface:** \
