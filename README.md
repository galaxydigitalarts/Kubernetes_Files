# Kubernetes_Files

This is a sample dockerfile that automated most of the phpIPAM installation using the Centos8 image from Docker Hub.

Once the container is created, exec into it and run sudo mysql_secure_installation to choose your root password for the database. 

Then, open a browser window on the host and enter the container IP port 80 to acess the application setup screen. 

Follow the official instructions https://phpipam.net/phpipam-installation-on-centos-7/ starting at step 3.

Note: selinux is disabled by default