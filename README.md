# Linux-Server-Configuration-Project

### Project OverView
> * A baseline installation of a Linux server and prepare it to host  web applications. As well as Securing server from a number of attack vectors, install and configure a database server, and deploy one of existing web applications onto it.

### Why this Project?
> * A deep understanding of exactly what your web applications are doing, how they are hosted, and the interactions between multiple systems are what define you as a Full Stack Web Developer. In this project, you’ll be responsible for turning a brand-new, bare bones, Linux server into the secure and efficient web application host your applications need.

## Server details
   > * Public IP address: 18.195.83.125      
   > * SSH port: 2200                                 
   > * URL:

### 1- Having a Server
> * Start a new Ubuntu Linux server instance on [Amazon Lightsail](https://lightsail.aws.amazon.com/).

### 2- Connect to your Server using SSH

* Create a directory.        
> * mkdir -p ~/.ssh

* Move the downloaded `.pem` file to `.ssh` directory we just created.    
> * mv key.pem ~/.ssh
> * sudo chmod 400 ~/.ssh/key.pem

* Connect to instance.
> * ssh -i ~/.ssh/key.pem ubuntu@18.195.83.125


### 3- Update all currently installed packages

  > *  sudo apt-get update
  > *  sudo apt-get upgrade
