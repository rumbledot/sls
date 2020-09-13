# A Serverless experiment

I found Serverless tutorial while trying to solve API Gateway problem that I had.

Turns out this framework is very handy and easily setup using NPM! And it offers langguages that supported by AWS.

I am confortable with JavaScript.

Serverless CLI is easy to use and will help you link to AWS account using their online dashboard.

Everytime we change and save our local code, it will automatically sync it to AWS S3 and have the option to redeploy the API.

Before using it, I need to remove the .js files in S3 and upload the new one. Go to API Gateway service page, update the Lambdas and redeploy it.

And always find my self puzzled why the API stop working and throwing tantrums. I forgot to redeploying it!

A note to Windows 10 user, don't use the CLI using VSCode default Powershell. It always failed to read the environment variables. 

It works best using Git bash or other Windows 10 Linux terminal.
