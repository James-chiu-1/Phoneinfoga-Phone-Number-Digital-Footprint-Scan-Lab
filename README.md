Phoneinfoga Phone Number Digital Footprint Scan Lab</h1>

<h2>Description</h2>
In this project we are going to download Phoneinfoga on Oracle vm virtualbox to check a phone numbers digital footprint. 

<h2>Languages and Utilities Used</h2>

- <b>Terminal Emulator</b> 

<h2>Environments Used </h2>

- <b>Kali-Linux</b> (21H2)

<h2>services used </h2>

- <b>Oracle</b> 

- <b>Virtual Machines</b> 

- <b>VirtualBox Manager Player</b> 


<h2>Program walk-through PT.1:</h2>


- <b> We are going to open our virtual machine and open firefox to look for the Github download instructions for Phonefoga. 

 
   <img src="https://i.imgur.com/rsYyvXJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 
   <img src="https://i.imgur.com/JXwiCXw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


 - <b> Now we are going to type "curl -sSL https://raw.githubusercontent.com/sundowndev/phoneinfoga/master/support/scripts/install | bash" into the VM Terminal to download the lastest release in the current directory. It should look like the picture below.
 
 
  <img src="https://i.imgur.com/aLVW3vj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 

 - <b> With the current directory downloaded we can now download the actual phonefoga. type "sudo install ./phoneinfoga /usr/local/bin/phoneinfoga" into the VM terminal. The terminal will then ask you for for you Kali-Linux user passsword. The terminal should now have the tool downloaded while showing no indicators.
 
 
   <img src="https://i.imgur.com/aLVW3vj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 
- <b> Now that we have downloaded phonefoga we need to type "./phoneinfoga version" to see if our phonefoga is up-to-date. 
 
 
  <img src="https://i.imgur.com/CxN3jNh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 
- <b> Now we will run a scan on a phone number to check the digital footprint of the number. Type "./phoneinfoga scan -n **********" and press enter to get the footprint. (********** is the phone number)
 
  <img src="https://i.imgur.com/KaTV1yg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 
- <b> Bravo! we have successfully scanned a phone number in phoneinfoga to check it's  digital footprint. 


 

 
 
 
 
 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
