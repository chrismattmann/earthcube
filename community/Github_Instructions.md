Guide for Contributing your project to Github
=============================================
Please follow these instructions for contributing your project
to Github!

1. download and install hub.github.com
2. follow this guide to make sure that you have Git SSH keys:
https://help.github.com/articles/generating-ssh-keys/
  TL;DR version:
   a. ssh-keygen -t rsa -C "your_email@example.com”
   b. don’t use a passphrase (will be annoying if you later)
   c. grab the value out of $HOME/.ssh/id_rsa.pub and then 
go over to your Github account > Settings > SSH keys and paste
the value of the id_rsa.pub file into the key setting.
3. mkdir -p $HOME/src/<your project name>
4. cd $HOME/src/<your project name>
5. edit and add a README.md file.
6. edit and add a LICENSE.txt file (suggestion: Apache License, version 2)
7. add your pom.xml file and/or setup.py file and/or .PM file.
8. add your dependencies.
9. git init (to initialize your working repo in this dir)
10. git add * (to add all the uncommitted files)
11. git commit -m “Initial commit”
12. git create 
13. git push origin master
14. visit https://github.com/<your username>/<your projedt>.git and there
is your project!
