+++
title = "Testing"
chapter = false
weight = 20
+++

## Testing

Once you feel your workshop is complete, have a few other people test it. At this point you will probably need technical people to test it as the flow may be a little rough.  `hugo` with no options will generate an html site in `/public`. But it's also fairly easy to run `hugo server` and connect to `localhost:1313` to view the workshop.

Once you have ironed out flow issues, have a few non-technical check the site for grammatical errors.  If you are using an IDE, which I hope you are, install or setup spell check to catch some mistakes early.


### Test Event Engine Permissions


Click [here](https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/create/review?templateURL=https://modernization-workshop-bucket.s3-us-west-2.amazonaws.com/cfn/ee/teamrole-testing.yaml&stackName=EE-TeamRole) to create the appropriate role and permissions in your account.  Once the stack completes click near the upper right on your username and account and select switch role.  Type your account, Role: ```TeamRole```, Display Name and click **Switch Role**.  Now start testing using a role and permissions policy that Event Engine uses for the workshop.


### Test on Event Engine

Request a Dev event to run through the workshop on Event Engine

#### Some things to check for

* Check for flow and make sure that someone following the instructions can complete the workshop
* Make sure there are no errors when going through the different steps
* Check all links in the workshop and the navigation
* Check the `search` functionality
* Ensure you cleaned up all resources



