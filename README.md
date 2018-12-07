The purpose of this repository is to properly configure and install Red Hat Openshift as a homework assignment

Getting files and installing OpenShift:
1.	Login into Bastion

2.	Login to installation user:
    sudo -i
    
3.	Change to the repository directory:
    cd /usr/share/ansible/
    
4.	Download files from GitHub:
    git clone https://github.com/Bo1337/ocp_advanced_deployment_homework.git
    
4.	Change to the repository directory:
    cd /usr/share/ansible/advanced_deployment_homework/
    
5.	Install OpenShift and output the install to a log file at /var/logs/install.log:
	ansible-playbook /usr/share/ansible/advanced_deployment_homework/homework.yaml