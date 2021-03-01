# vscode-linux-package
vscode-server tar package for local install for RHEL/Centos Linux

To Install in RHEL/CENTOS, use the RPM package from releases
rpm -ivh <package_name>
-----------------------
To run 
code-server 
-----------------------
Optionally configure additional options under ~/.config/code-server directory. 
-----------------------
To remove
-----------------------
rpm -qa | grep code-server 
rpm -e <exact_package_name>
