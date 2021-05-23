---
author: avsravindra
---

# Installer

Use the following steps to run the Installer

1) You can perform the Installation from the same location where installer script is available. Currently, Blaize do not support the custom option, which you can mention during installation.

2) Run the following command to make the installer executable:
  
   chmod ugo+x <<installer>> 
   where installer is Blaize_Installer_SDK_X.X.XX.sh (X denotes the sdk version).

3) Command-line options are available when we execute the installer followed by '-h' option. 
	- By default, Blaize Python Virtual Environment (PyEnv) will be created, if you run the installer without any options. 
	- On GPU, NVCC path must be added in to the **$PATH** environment variable to detect Cuda driver. 

4) Once the installer is enabled to execute,  run the installer using the following command:
    
		./<<installer>>

------------
Author: {{ page.author }}

[mydoc](main/mydoc.md)

[README](main/README.md)