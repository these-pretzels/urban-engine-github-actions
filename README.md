Dope. This works. Github actions are triggered when I push to main.
All AWS secrets are stored in github, this needs to be updated each time a new sandbox is deployed.!
I can change the commands and the output will be shown in github actions page:

  aws ec2 describe-instances --instance-ids ***
 ...
 "InstanceType": "t2.micro",
                    "KeyName": "balha",
                    "LaunchTime": "2022-07-22T20:56:49+00:00",
                    "Monitoring": {
                        "State": "disabled"
                    },
                    "Placement": {
                        "AvailabilityZone": "***a",
...
