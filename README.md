.bashrc-passwordManager
=======================
A simple password manager made to placed in one's .bashrc file. Once added to .bashrc it is called via running passwordManager in bashI (terminal) . It works via prompting the user for a master password and the URL of the website they need a password for and then hashing the combination of those two strings. 

Installation
=======================
Run this command in terminal to install passwordManager. 

`cd ~ && git clone https://github.com/ddworken/.bashrc-passwordManager.git && cd .bashrc-passwordManager/ && cat passwordManager >> ../.bashrc && cd .. && rm -rf .bashrc-passwordManager/`
