# Problem
Need to install PowerCli on Windows

# Answer
Open PowerShell as Admin, run the command 
- Install-Module -Name VMware.PowerCLI -Scope CurrentUser -AllowClobber

# Reference(s)
- https://developer.vmware.com/powercli
- https://blogs.vmware.com/PowerCLI/2017/04/powercli-install-process-powershell-gallery.html


# Steps

# 1. Right Click PowerShell 

# 2. Select "Run as Administrator"
![image](https://user-images.githubusercontent.com/31425783/187043776-ed2bfec9-567d-416d-ae1d-6249c669c6e5.png)

# 3. Enter command below and press Y at the prompt
 Install-Module -Name VMware.PowerCLI -Scope CurrentUser -AllowClobber
![image](https://user-images.githubusercontent.com/31425783/187043713-a4e1317f-4fa3-40ba-9ac0-e9e9ab3ab602.png)


# 4. Test
 find-module -Name VMware.PowerCLI
![image](https://user-images.githubusercontent.com/31425783/187043831-3cfae6cb-e402-44b7-9feb-f1eb9e31bc28.png)

  
  
  




