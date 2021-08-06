### Setting up the firewall in ubuntu VPS

- ufw allow OpenSSH *allows only ssh connections and ufw stands for uncomplicated firewall*
- ufw enable *enables the firewall*

### Setting up a non-root user

- adduser <username> *only root users can add the user*
- usermod -aG sudo <username> *gives the user a sudo previliges*
  
### Updating the system
- sudo apt update *gives the information about the updatable files*
- sudo apt upgrade *updates the system*
