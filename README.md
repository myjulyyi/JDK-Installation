# Installation of the 64-bit JDK on RPM-based Linux Platforms

jdk-8uversion-linux-x64.rpm
Download the file.

Before the file can be downloaded, you must accept the license agreement.

Become root by running su and entering the super-user password.

Uninstall any earlier installations of the JDK packages.

# rpm -e package_name
Install the package.

# rpm -ivh jdk-8uversion-linux-x64.rpm
To upgrade a package:

# rpm -Uvh jdk-8uversion-linux-x64.rpm
Delete the .rpm file if you want to save disk space.

Exit the root shell. No need to reboot.
