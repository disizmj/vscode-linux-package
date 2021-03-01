# vscode-linux-package
vscode-server tar package for local install for RHEL/Centos Linux

To Install in RHEL/CENTOS, use the RPM package from releases<br />
rpm -ivh <package_name>
-
To run VS code-server <br />
code-server 
-
Optionally configure additional options under ~/.config/code-server directory. <br />
-
To remove package <br />
-
rpm -qa | grep code-server <br />
rpm -e <exact_package_name>
