# Installation of the 64-bit JDK on RPM-based Linux Platforms

jdk-8uversion-linux-x64.rpm
Download the file.

Before the file can be downloaded, you must accept the license agreement.

Become root by running su and entering the super-user password.

### Uninstall any earlier installations of the JDK packages.
<code><pre>
rpm -e package_name
</pre></code>

### Install the package.
<code><pre>
rpm -ivh jdk-8uversion-linux-x64.rpm
</pre></code>

### To upgrade a package:
<code><pre>
rpm -Uvh jdk-8uversion-linux-x64.rpm
</pre></code>

Delete the .rpm file if you want to save disk space.

Exit the root shell. No need to reboot.
