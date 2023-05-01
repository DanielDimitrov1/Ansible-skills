Create a role called new-apache in /home/tom/ansible/roles that enables and starts httpd, enables and starts the firewall and allows the webserver service.
Create a template called index.html.j2 which creates and serves a message from /var/www/html/index.html and whenever the content of the file changes, restart the webserver service.

Welcome to [FQDN] on [IP]
Replace the FQDN with the fully qualified domain name and the IP with the ip address of the node using ansible facts. Lastly create a playbook in /home/tom/ansible called apache.yml and use the role to serve the index file on prod hosts.
