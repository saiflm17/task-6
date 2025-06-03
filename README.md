# TASK-6 EXPLANATION 

- Now am deploying a static-cycle-website by using github pages .

#STEP-1 : am creating a new server with server configurations like server_name, AMI : AMAZON LINUX KERNEL 5.10, Instance_type : t2.micro, key_pair, security_group : All Traffic, EBS : 8 GIB . After launching the server and am connecting through SSH .

#STEP-2 : changing the root user by using command .

- COMMAND : sudo -i - to change the root user .

- Now am installing git tool by using command .

- COMMAND : yum install git -y .

- After am creating a New Repository in GitHub and Repository_Name : task-6 .

- so that repository am cloning into my local server by using command .

- COMMAND : git clone https_url - cloning into repository .

- Now am changing the directory   cd task-6 .

- After am creating some files index.html, news.html, cycle.html, contact.html, about.html and CSS, JS and also am taking some images from google and am collecting source code from chatgpt .

- Now am initializing the repository by using command .

- COMMAND : git init .

- Now am tracking the all files by using command .

- COMMAND : git add file_name - to track the files .

- COMMAND : git status - to check the status of the files .

- Now am committing the files by using command .

- COMMAND : git commit -m "commit message" file_name - to committing the file .

- Now am integrating the repository by using command .

- COMMAND : git remote add origin https_url - to integrating the repository .

- COMMAND : git remote -v - to check which repository have to integrate .

- Now am pushing main branch to github by using command .

- COMMAND : git push -u origin branch_name .

- After am deploying static-cycle-website by using github pages .

- repository settings 🡢 pages 🡢 Enabled github pages .

- select a main branch and root folder .

- Live website link here    https://saiflm17.github.io/task-6/
