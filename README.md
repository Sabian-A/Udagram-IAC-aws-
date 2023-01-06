Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the code for the "Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:

servers.yml
 CloudFormation code using this YAML template for building the cloud infrastructure(Resources), as required for the project.
 
network.yml
 CloudFormation code using this YAML template for building the cloud infrastructure(networking), as required for the project.

servers-parameters.json
 a JSON file for increasing the generic nature of the YAML code (servers.yml).
 
network-parameters.json
 a JSON file for increasing the generic nature of the YAML code (network.yml).
 
 Diagram.png
  a .png file showing the infrastriucture diagram to be deployed using coud formation. 
  
 URL.txt
  text file containing the  URL to verify the resources work properly. 
  
 workflow directory
 a directory containing all the screenshoots(aws consol) of the resources created using cloudformation.
 
 update.sh and creat.sh 
   scripting files for creating and updating the cloudformation stack
   
 Simple index.tml file  
 (Disclaimar!!) I have used a simple index.html that i have found on the internet (not my work!) to demonstrat that my instance is pulling   the  html file from my s3 bucket.  
 
 I have referenced aws official documents and other resources from the internet to help me finish tis project.
