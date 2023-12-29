# Deploy-a-Static-Web-Application-Using-Ansible
Deploy a Static Web Application to a remote Server Using Ansible using these steps:


Create your ec2 instances


Obtain or clone a sample web application: For this project, we cloned a demo site via this link https://github.com/do-community/html_demo_site.git


Create an Nginx Conf. File


Set up your playbook on the Ansible control node. Your playbook should contain the following:
- Installation of necessary packages ie Nginx webserver
- Copy application files to the server's root directory
- Apply and enable the Nginx Configuration template on the server
- Open Port 80 using the UFW module
- Set up handlers for the Nginx Services 


Run your playbook - eg ansible-playbook *playbook-name.yaml*
