+++
title = "Testing"
chapter = false
weight = 20
+++

## Testing

As you are creating your workshop, test through the steps you are writing down for the customers. This will ensure each part of the workshop is functional and working. When you feel like the workshop is technically complete, have a few other technical people test it. For now, have them run `hugo server` and connect to `localhost:1313` to view the workshop and follow the steps.

Once you have ironed out flow issues, have a few non-technical check the site for grammatical errors. If you are using an IDE, which we hope you are, install or setup spell check add-ons to catch some mistakes early.


### Test Self Guided Permissions

You will need your own, or your company's AWS account to provision all the required infrastructure to run through the workshop. 

### Test Event Engine Permissions

You will need to contact your PSA to help provision non-prod Event Engine accounts so that both your team and the PSAs involved can test the workshop end to end.

Click [here](https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/create/review?templateURL=https://modernization-workshop-bucket.s3-us-west-2.amazonaws.com/cfn/ee/teamrole-testing.yaml&stackName=EE-TeamRole) to create the appropriate role and permissions in your account.  Once the stack completes click near the upper right on your username and account and select switch role.  Type your account, Role: ```TeamRole```, Display Name and click **Switch Role**.  Now start testing using a role and permissions policy that Event Engine uses for the workshop.

#### Some things to check for

* Check for flow and make sure that someone following the instructions can complete the workshop
* Make sure there are no errors when going through the different steps.
  * If there are inevitable pitfalls, add tips or notes shortcode to those pages to notify the attendees
* Check that links in the workshop are not broken
* Check the `search` functionality
* Check the cleanup section (if applicable) will not incur additional costs



