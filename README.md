# Fall2021-CEG2350

Lab &amp; Materials for CEG 2350

## Troubleshooting

### Remaking your AWS Educate environment

The steps below should only be needed if you lost your key from AWS Educate. If you still have your key but your enviromnent is broken, only follow steps 1-2, then go back to Lab 01 and rebuild your stack.

1. Go to the Services dropdown, under Management and Governance, select CloudFormation
2. Select your Stack, then select Delete
   - It is important to remove old stacks. Each stack has a charge associated with it, so you risk running out of funds for this course. While fixable, this will delay your ability to complete labs on time.
3. Go to the Services Dropdown, under Compute select EC2
4. Select Key Pairs
5. Select your key pair(s) and select Delete.
6. Recreate your environment by following the steps in the [Lab 01](Lab01/) guide

### I have a Chromebook, and ssh in Terminal isn't working...

This guide here refers to a [Chrome Extension for SSH connections](https://www.lifewire.com/how-to-use-chromebook-ssh-client-4690108)

- To use your AWS Educate Private Key, you'll need to select "Import..." and browse to your  
  key file - you can then select your key from the dropdown.
- You may need to make a "failed" connection in order to get the permission to access files  
  questions to pop up.
