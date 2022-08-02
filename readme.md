
## Installation method

Run the './install.sh 'command to automatically compile, install, and start the Lorawan gateway service, and configure it to start automatically upon startup



## Precautions

1. During the install.sh execution, SCP will be used, keyGen will be generated, and a dialog will be displayed. Press Enter

2. When you run install.sh, you may be asked to enter the password. The default user name and password are admin and admin.

3. The gateway ID is automatically generated. The rule is FFFE +MAC address. For example, if the MAC address is 00:01:02:03:04:05, the generated gateway ID is FFFE000102030405

4. The default gateway only wants to be the Tencent cloud development platform

5. Executable files and configuration files are installed in the $HOME/sx1302/bin directory. If you want to modify the frequency point information and gateway direction, modify the global_conf.json file in this folder
