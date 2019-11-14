# Exercise 1

loadbalance 4 **Docker** Container in which each 2 will be running with *Ubuntu* and *CentOS*
one loadbalancer with *Ubuntu*. All these servers will run **nginx** as webserver. **nginx** in
loadbalancer server will act as load balancer

   + Created 2 Ubuntu:16.04 version Docker containers **App Servers**
   + Created 2 CentOS:7 version Docker containers  **App Servers**
   + Created 1 Ubuntu:16.04 version Docker containers **Load Balancer**
   + Install Nginx in all App Servers
   + Configure the web root folder
   + Copy the default html file using jinja
   + Install Nginx in loadbalncer server
   + Configure default file locally and copy to lb container
   + Created this in organized manner
   + Run ansible playbook `ansible-playbook -i hosts install-nginx.yml`

>All script  files were created manually
