To Install Jenkins from repo
https://pkg.jenkins.io/
Log in to Jenkins.
Go to Manage Jenkins > Manage Plugins.
In the Available tab, search for "Docker Pipeline".
Select the plugin and click the Install button.
Restart Jenkins after the plugin is installed.
sudo apt update
sudo apt install docker.io
sudo su - 
usermod -aG docker jenkins
usermod -aG docker ubuntu
systemctl restart docker
http://<ec2-instance-public-ip>:8080/restart
