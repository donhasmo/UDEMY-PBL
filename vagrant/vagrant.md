
# Using vagrant to automate virtual machines
## Prerequisites 

-Open your browser and search for `install chocolatey for windows/MacOS` depending on your system

 Open powershell as administrator ![](./img/powershellAdm.PNG)

-Follow the steps to install chocolatey using powershell

-Run `choco -v` on powershell to see the chocolate version and confirm installation ![](./img/chocoV.PNG)
-Install Oracle VM VirtualBox

-Search vagrant cloud on your browser

-Search centos 9 on vagrant cloud. ![](./img/vagrantCloud.PNG)

-Copy the command to install the required centos 9 image.

-Create a vagrant-vm folder in your preferred location

-Inside the vagrant-vm folder, create a folder with the name of the OS you want to install. In our case, (centos 9).

-`cd` inside the folder of the OS, type `vagrant init` followed by pasting the command you copied from vagrant cloud.

-`ls` to see the Vagrantfile and also confirm successful installation ![](./img/vagrantBox.PNG)

-`vagrant up` to start the VM ![](./img/vagrant-up.PNG)

-Go to Oracle VM virtualBox to confirm the if the VM is up ![](./img/vmboxCHK.PNG)

-`vagrant status` to see status of VM on command prompt ![](./img/vagrant-status.PNG)

`ssh vagrant` to ssh into the centos 9 VM

`exit` to leave VM

-`vagrant halt` to stop VM

- Repeat same steps for ubuntu using the name "ubuntu jammy"
![](./img/vag-ubuntu.PNG)
![](./img/install-ubuntu.PNG)

