# vagrant-devops-env

The code in this repository is meant for setting up a full K8s environment meant for home study.

System requirements:
For just only a K8s environment, it is necessary to have a system with atleast 6 to 8GB of memory and 6 CPU cores. 

For making this work:
- Windows 11 professional (Windows 10 professional should also do the job):
- Latest version of Virtualbox   
- Default WSL2 installed with following software:
  - Ansible-2.16+ (Installed by DEB packages)
  - Vagrant and the following Vagrant plugins:
    - virtualbox_WSL2
    - Vagrant-env
    - Vagrant-git
          
This code is experimental by default and is not even by the slightest production-ready. By using this code, you acknowledge the risk that it may break. 
