#Installations
## Install AWS CLI
###Prerequisites
Before you can install the AWS CLI version 1 on macOS, be sure you have Python 2 version 2.7 or later, or Python 3 version 3.6 or later installed

1. curl "https://s3.amazonaws.com/aws-cli/awscli-bundle.zip" -o "awscli-bundle.zip"
2. unzip awscli-bundle.zip
3. sudo /opt/homebrew/bin/python3  awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws
4. Verify that the AWS CLI installed correctly.
aws --version

## Install Git
## Intall Visual studio code
1. brew install --cask visual-studio-code
2. Add Bash alias in .bash_profile ?
alias code="open -a /Applications/Visual\ Studio\ Code.app"
3. Open Visual Studio Code by command
code 

## Install Terraform Latest Version
1. brew install terraform