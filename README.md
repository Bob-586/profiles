# profiles
Bash Aliases

# INSTALL:
Download from guthub to /home/$USER/profiles and extract there...

Then: sudo mv /home/$USER/profiles/ /opt/

Next: goto this folder: cd /opt/profiles

Now, as a non-Root USER from a console: ./install.sh

# If not using the install.sh installer follow these steps:

# First Backup any changes to these files, then remove them:

mv /home/$USER/.bash_aliases /home/$USER/.old_bash_aliases

mv /home/$USER/.bashrc /home/$USER/.old_bashrc

mv /home/$USER/.profile /home/$USER/.old_profile

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
