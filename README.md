# Ansible

This repo is to give to basic knowledge of ansible with a project to get handson even if you haven't made any playbooks yet this repo can help you and you will get good understanding of ansible. 

# Ansible and its modules 

Ansible is an open-source automation tool that can be used for a variety of tasks, including configuration management and deployment automation. One of the key features of Ansible is the ability to use it in a continuous integration/continuous deployment (CI/CD) pipeline.

CI/CD is a set of practices that aims to streamline the process of building, testing, and deploying software. Ansible can be used in the CI/CD pipeline to automate the deployment of software and ensure that it is consistent across different environments.

Ansible uses modules to perform various tasks. 

Modules are reusable pieces of code that can be used to automate specific tasks. For example, there are modules for managing users and groups, installing software packages, and configuring network settings.

ansible module is a command or set of commands to be executed on the client side and it has numerous modules for aws azure to autoamte tasks accordingly.

Ansible includes a large number of built-in modules, and it is also possible to write custom modules if needed. When using Ansible, modules are called with parameters, which can be used to customize their behavior. For example, when installing a package using the "apt" module, parameters can be used to specify the package name and version.

Overall, Ansible's CI/CD and configuration management capabilities, as well as its extensive library of modules, make it a powerful tool for automating IT tasks.

Ansible is an open source configuration management tool that YAML as a scripting language, work on push management where One Ansible master can control configuration of slave servers, it is agentless and works through SSH to perform tasks.


As a Devops engineer we are required to do certain task install packages and webstacks on the server so lets say you are asked to deploy wordpress apps on the servers, logging into 10 servers than performing taks can be tiring this is where ansible comes to the rescue the master branch has playbooks where you can easily deploy docker on the slave servers install wordpress on all the slave servers with LAMP stack. 