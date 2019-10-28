# Steps if Bash Shortcut:

1. Navigate to the severlesss.yml file and replace the two lines with comments with the relevant values
2. Note, both of those lines are in regards to a dynamoDB table. If you don't want to have the dynamoDB tables, delete lines 9-19 (inclusive)
3. Configure Lambdas as desired
4. Run ```sls deploy``` to deploy the code


# Steps if Downloaded from git:

1. ```npm install```
2. Navigate to the severlesss.yml file and replace the two lines with comments with the relevant values
3. Note, both of those lines are in regards to a dynamoDB table. If you don't want to have the dynamoDB tables, delete lines 9-19 (inclusive)
4. run ```aws configure``` and use the credientials (run custom bash script ```aws_configure``` to get credentials)
5. OPTIONAL: If you want to gen new credentials, go to AWS, click your name, in the drop down, choose My Security Credentials > Access Keys > create new key 
6. Configure Lambdas as desired
7. Run ```sls deploy``` to deploy the code
