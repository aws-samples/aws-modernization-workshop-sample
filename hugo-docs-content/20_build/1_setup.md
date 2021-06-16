+++
title = "Setup Environment"
chapter = false
weight = 1
+++

Building a workshop leverages several tools:

* Git
* Hugo
* Hugo learn theme
* CloudFormation templates

## 1. Clone Sample Repo
AWS Modernization Workshops are powered by the [Hugo Framework](https://gohugo.io/about/what-is-hugo/). Hugo uses markdown files to generate HTML assets so if your experts have experience with writing documentations on GitHub README's, this should be very familiar!

If not, that is also OK as there are a plethora of documentations to help out someone just starting.

{{% notice note %}}
To make the creation of web page documentation easier, we utilize a tool called Hugo.  You will write your documentation/instructions using Markdown language and Hugo will create static HTML content that can be served via S3. Hugo additionally applies a theme so that the site will have an AWS look and feel plus add additional features to beautify and make content stand out.
{{% /notice %}}

Start by cloning the base repo and push it to a repo on your own GitHub account. Change the name of myCompany-Workshop :) 
```
git clone https://github.com/aws-samples/aws-modernization-workshop-base myCompany-Workshop
```
> We use clone instead of fork as you will break this from the sample repo and change the name. Once approved and published the repo will be called something to the effect aws-modernization-workshop-with-Company_Name

## 2. Download submodules
The repo uses git submodules so run the following commands at the root of the newly cloned repo:
```
git submodule init
git submodule update
```
The submodules contain the hugo-theme-learn theme for the Hugo Framework.
{{% notice tip %}}
**For more information about hugo-theme-learn used in AWS Workshops, visit** https://learn.netlify.com/en/
{{% /notice %}}

## 3. Create and push to YOUR GitHub repo

**Create a repo in your GitHub account and follow the instructions under "Push an existing repository from the command line"**

## 4. Install Hugo
If you're using a Mac, go to your terminal:
```
brew install hugo
```
If you're using a Window, go to your command line:
```
choco install hugo -confirm
```

{{% notice tip %}}
**For more information about installing and using Hugo, visit** https://gohugo.io/getting-started/installing/
{{% /notice %}}

## 5. Running Hugo
From within the root of the repo
``` 
$ hugo server
```
Using a browser go to http://localhost:1313 to view the site.  Hugo is dynamic, so as you edit the content, and the page in the browser will change.  Allowing you to view in real-time what the content will look like.
