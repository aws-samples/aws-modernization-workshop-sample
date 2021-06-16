+++
title = "FAQs"
chapter = true
weight = 40
+++

## FAQ's

**Why do you use Cloud9?**

Answer: When conducting workshops it is often difficult to determine the state of the users workstation and validate that all dependencies and requirements are installed.  With Cloud9 we get a capable IDE and shell access to the AWS account.  Git, aws-cli, programming languages, and many other tools are pre-installed which allows us to start everyone from a known state and not have to fumble around with missing components from someone's workstation.  

**Can I change the License?**

Answer: We rather you not.  The site will be posted at aws-samples and the license included in the sample is MIT, which is meant to be simple and open source friendly.  

**What if I want to use other tools, such as Jenkins or Terraform as examples?**

Answer: Great. We actually encourage you to use other tools and services as you may expect customers to use this in their environment.  Note that if you choose to use additional or alternative tools that it's easy for the end user to follow and does not detract from your main message.  As an example, if your main message is application security scanning, does it make a difference whether you use Jenkins or CodeBuild, or does the usage of one, or the other add unnecessary complexity that has nothing to do with your message?  So don't reinvent the wheel and if there is already an example of instrumenting testing in CodeBuild, I would use that as the tool has nothing to do with your message.  But if your main message is instrumenting security scanning on Jenkins, then yes, use Jenkins.

**How long does a workshop take to create?**

Answer: As little as 3 days and as long as 2 months.  If the workshop creator is familiar with git, markdown, and AWS the content can be created in as little as 3 days, which includes testing out the workshop flow.  If the user is not familiar with some of these tools, there is a learn curve they will need to overcome.  Additionally, dedication also plays a factor.  To complete the workshop in 3 days requires full dedication.  If someone is splitting time with their "day job" and workshop creation then it can be expected to take longer.  

**What skill level are workshop participants?**

Answer: The spectrum varies from not familiar to experts.  Don't assume workshop participants are familiar with AWS and you should include links to areas of the console you want the user to navigate to.  

**How long should a workshop be?**  

Answer: The typical length of a workshop should be around ~2 hours to complete. We have noticed that if it takes any more time the user will lose interest, and you may have a problem with drop-outs. If your content is longer than 2 hours, consider breaking it up into multiple modules. 

**Tip:** If breaking up into multiple modules, create a flow that participants can start up a new module without having to go back through previous modules again.  This allows workshop users to take breaks that may span days between modules.  This is typically accomplished by automating steps the participant followed in previous modules.

