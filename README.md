# Deploy-a-Static-Web-Application-Using-Ansible
Deploy a Static Web Application to a remote Server Using Ansible by following the steps below:

![image](https://github.com/etidoumossoh/Deploy-a-Static-Web-Application-Using-Ansible/assets/113789743/8f153b9d-ed5d-4114-8116-99e1edef85e4)



# STEP ONE: Set Up Two EC2 Instances 
Create your ec2 instances. Install Ansible on your controller- node


# STEP TWO: Clone Git Repo
Obtain or clone a sample web application: For this project, we cloned a demo site via this link https://github.com/do-community/html_demo_site.git

# STEP THREE: Create Nginx Configuration Template
Create an Nginx Conf. File

# STEP FOUR: Create Ansible PlayBook
Set up your playbook on the Ansible control node. Your playbook should contain the following:
- Installation of necessary packages ie Nginx webserver
- Copy application files to the server's root directory
- Apply and enable the Nginx Configuration template on the server
- Open Port 80 using the UFW module
- Set up handlers for the Nginx Services 

# Execute your PlayBook
Run your playbook - eg ansible-playbook *playbook-name.yaml*


