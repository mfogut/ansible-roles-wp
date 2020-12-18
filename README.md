# Create Ansible-Galaxy Roles
- ansible-galaxy init server
- ansible-galaxy init php
- ansible-galaxy init mysql
- ansible-galaxy init wordpress

# Install Required Software with Server Role
- apache2
- mysql-server
- php7.4-mysql
- php7.4
- libapache2-mod-php7.4
- python3-mysqldb

# Install PHP Extensions with PHP Role
- php7.4-gd                
- php7.4-ssh2

# Create MySQL Database and DB User with MySQL Role

# Install Wordpress to DB Servers
- Download WordPress
- Extract WordPress
- Update default Apache site
    - Restart Apache2 with handlers
- Copy sample config file
- Update WordPress config file

# Run Ansible Playbook in order to apply changes
- ansible-playbook playbook.yml
Note : Playbook file must be same level (in same directory) with your roles.

# Hit domain name or Ip address from your web browser in order to verify exit criteria
