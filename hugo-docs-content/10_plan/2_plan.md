+++
title = "Plan the Workshop"
chapter = false
weight = 10
+++

### High Level Workshop Planning
1. Determine what problem/use case your solution solves.
    * Remember to wrap your story around this so customers find it useful. For example: I want potential customers to learn how easy it is to instrument our testing product into their build pipeline.
1. Determine what concepts about your solution you want the customers to learn about.
1. Think from a high level what components or systems will be needed. These are the building blocks that will save you time when you start to build the workshop. Don't re-invent the wheel. Link to content for account creation and other artifacts you will need.
1. Think about what AWS services that you'll need for your workshop.
    * Are you a Kubernetes management/CD partner? You'll probably need an EKS cluster in your customer's account.
    * Is your CI/CD solution completely abstracted and requires permissions to automate the provisioning and management of the pipeline? You'll probably need AWS access keys.
    * If necessary, create an architecture diagram that can help both you, and the workshop attendees on how the pieces all fit together.
1. Determine the workflow or stages. 
    * You are telling a story, which means:
        * An introduction section that details what problem you'll be solving and what the customers will accomplish with the workshop 
        * The educational body of the workshop (separated into modules)
        * The conclusion that ties all the pieces together.
1. **Don't forget a cleanup section as well**. Customers will be deploying AWS resources, and we want to make sure they are not charged more than what is necessary to learn about your solution.
1. Identify what event this workshop will be presented at. Will it be AWS hosted, partner-instructed event? Or will it be marketed as a self-paced workshop?
    * This is important as it will change the flow/set-up instructions.
    * i.e. using Event Engine (more about this later) at an AWS hosted event with pre-provisioned infrastructure 
1. Have a way to capture leads! This is the end goal.

### Workshop Planning Best Practices
* Thought about all the above? Write it down in an abstract to send to your PSA for review!
* The abstract can have the architecture diagram that can be used to help the attendees understand what is going on.
* Creating a **GREAT** workshop takes a lot of effort - the individuals involved will spend a combined **30+ hours** on researching, writing, testing, revising the workshop.
    * Another way of saying: there should be significant buy-in via dedicated experts to see this project end-to-end.
* Create the content **well in advance** of the date of when the workshop will be launched.
    * Trying to create a workshop 4 weeks before a launch/target date means an all-hands on deck situation. Lots of unnecessary stress due to a tight deadline.
    * The PSA involved will pull the plug if the quality of the workshop is compromised so give yourself breathing room by doing this in advance.
* Test your workshop as you create it - the things you're figuring out in the last module won't mean anything if the first module doesn't work.
* Keep your PSA/PDM involved throughout the process - we're all in this together and AWS wants you to succeed. 