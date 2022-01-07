1. We will need a file named hosts.ini, we will specify there IPs of our target machines, one for app and one for proxy
2. We will run commands as root by specifying "become: yes"
3. We also need some variables like repo name and URL.
4. Now are gonna install essential packages like python, pip, and git
5. After that we will download our repository
6. Now we are able to create our virtual environment for python and install all requirements
7. Last thing to do on this machine is to register our app as a service(in app.service that we need to copy as well) and run it
8. And now for our proxy machine
9. We need to install Nginx and EPEL
10. We will specify Nginx config and copy it to our machine
11. After reloading Nginx we should have both flask app and proxy

![alt text](https://github.com/OskarKozaczka/flask-app-ansible-automation/blob/main/diagram.png?raw=true)
![alt text](https://github.com/OskarKozaczka/flask-app-ansible-automation/blob/main/fl.png?raw=true)
