# profiles
Bash Aliases

# INSTALL:
Download from guthub to /opt/profiles and extract there...

# First Backup any changes to these files:

rm /home/$USER/.bash_aliases

rm /home/$USER/.bashrc

rm /home/$USER/.profile

# Make links to Bash Aliases:

ln -s /opt/profiles/.bash_aliases /home/$USER/

ln -s /opt/profiles/.bashrc /home/$USER/

ln -s /opt/profiles/.profile /home/$USER/

ln -s /opt/profiles/.git_svn_bash_prompt /home/$USER/

exit && relog in... for changes to take effect

# Usage:

for list of all commands/aliases type: commands

see list of scripts type: command

After command : type filename without the .env extension.

example: command web

ex2: command git

ex3: command apt_get

ex4: command docker

ex5: command folders
