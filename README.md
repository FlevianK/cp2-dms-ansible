# cp2-dms-ansible
Automate cp2-dms app to run on ubuntu vm using ansible, vagrant and virtual box.
Simple deployment scripts.

# Procedure for running the system locally
## Prerequisites
Ensure you have Ansible and Virtualbox installed.

## Installing
* Open to tab/window on your terminal
* Clone this repository [here](https://github.com/FlevianK/cp2-dms-ansible.git)

## To deploy fronted
> Navigate to the fronted folder of the system on your terminal and perform the following operations:
```sh
$ vagrant up
```

> Verify the deployment by navigating to your server address in your preferred browser.
```sh 
$ 127.0.0.1:8080
```
### To drop into the virtual machine
```sh
$ vagrant ssh
```
### To exit the virtual machine
```sh
$ exit
```
### To destroy virtual machine
```sh
$ vagrant destroy
```
## To deploy backend
> Navigate to the backend folder of the system on your terminal and perform the following operations:
```sh
$ vagrant up
```

> Verify the deployment by navigating to your server address in your preferred browser.
```sh 
$ 127.0.0.1:8000
```
### To drop into the virtual machine
```sh
$ vagrant ssh
```
### To exit the virtual machine
```sh
$ exit
```
### To destroy virtual machine
```sh
$ vagrant destroy
```
## Note
> If frontend is deployed, the application will use the backend hosted on Heroku. It will access the local backend if in case the backend on heroku fails to opperate correctly.
# Author
*** Flevian Kanaiza ***