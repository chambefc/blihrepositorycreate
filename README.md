# blihrepositorycreate

# INSTALLATION

1. First you need to configure the script to use your own ID.
  Convert your Epitech password in sha 512 using any website like :
  http://www.timestampgenerator.com/tools/sha512-generator/
  
  Then change the LOGIN and PASSWORD variables in the script with your own info (your epitech address for LOGIN and
  your password converted in SHA512 for PASSWORD).

2. To install the script, you have to copy it in your /usr/bin/ folder, using sudo.
  E.g. $ sudo cp scriptblih /usr/bin/

3. Then to use it, create an alias in your bashrc / zshrc or whatever with the name of the script with a dot and a blank space :
  E.g. alias createrepo='. scriptblih'
  
  THE DOT AND THE BLANK SPACE ARE VERY IMPORTANT DON'T FORGET IT ! You can copy the example above and paste it directly in your bashrc.

# DESCRIPTION

This script allows you to create an Epitech repository, set its ACL to ramassage-tek in readonly mode and eventually, other users.

To create a repository just call the alias you created such as createrepo followed by the name of your desired repository and you can add multiple users after the name of the repository to give them read write rights on the repo.
The script will set the ACL then clone the repository in the current folder and move your terminal inside the repository folder.
