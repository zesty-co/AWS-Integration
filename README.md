<img align="right" width="250" src="https://appa.zesty.co/assets/logo/zesty-logo.svg">

# AWS - Integration IAM Role
The Zesty journey starts with a 5-minute onboarding in which the customer [signs up](https://app.zesty.co/home/register) to Zesty Platform and provides a Read-Only IAM Role.  

Zesty does not store any private keys, passwords, or authentication tokens.  
The authentication is made based on the [IAM Cross Account Role](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_cross-account-with-roles.html) alog with External ID that provides two-factor authentication.

Our integration IAM Role provides read-only access to the metadata about the running resources in your AWS account.  
We never access any of your company or customer’s data.  

This step will allow Zesty to populate the Live Cloud Cost Dashboard and display within minutes an estimation of the potential savings using Zesty Automation.  

For more information regarding our security policies and complience, please visit https://zesty.co/security-overview/
