# Sources

## EC2 User Guide
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/AWS_EC2.html

## EC2 Instance User Guide
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-ec2-instance.html

- AvailabilityZone
- ImageId
- InstanceType
- UserData

# Tips

## List profiles
 aws configure list-profiles

## Select profile
export AWS_PROFILE=user1

## use a Profile for a specific aws command
--profile profile-name

## Make a sh file executable
sudo chmod +x filename.bin