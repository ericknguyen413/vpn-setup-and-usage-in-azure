<p align="center">
 
![image](https://github.com/user-attachments/assets/631445ef-105b-4349-9a57-cc95678c7928)

<br />

<h1>How to Setup and Use a VPN | ProtonVPN</h1>

 ### [YouTube Demonstration](https://youtu.be/_Jwpo0GfadQ)

<h2>Description</h2>
In this project, I create an Azure VM (Virtual Machine) where I download, install, and use a free VPN (Virtual Private Network) called ProtonVPN. <br />
<br />
VPNs (Virtual Private Networks) allow you to connect to a network through encrypted tunnels, enhancing security. Two common ways VPNs are used are for companies to allow for remote work and access different content that otherwise would be unavailable without a VPN.  
<br/>

<h2>Environments and Utilities Used</h2>

- <b>ProtonVPN</b>
- <b>Microsoft Azure</b>

<h2>Project Walk-through:</h2>

<p align="center">

First, I will create an Azure VM:

![image](https://github.com/user-attachments/assets/52c6fc6c-8a73-419d-8f1d-85a92112f5af)

![image](https://github.com/user-attachments/assets/d8686cc1-6118-4d9d-b4c0-9a097feb49bf)

While that's creating, I will navigate to this website https://whatismyipaddress.com to get my IP address and location. I will write this down in my notepad so that I can observe the changes later when we connect to our VM:

![image](https://github.com/user-attachments/assets/27f8ce4c-41fa-4d81-b33c-6412985b61eb)

Next, I'll connect to the VM I just created using Remote Desktop Connection:

![image](https://github.com/user-attachments/assets/94e185e8-e4df-4b50-8c1d-6ef1a343a87b)

Once I'm connected to my VM, I will navigate to the same IP website, then observe and note the different IPs and locations since I set this VM up to be in Canada. (This RDP connection is like a VPN connection in the sense that there is a tunnel connecting my physical computer to the VM in a different location entirely):

![image](https://github.com/user-attachments/assets/ad7bae38-e9c5-4e23-94b2-f72dee2f41f1)

Now, I can head over to ProtonVPN and sign up for a free account:

![image](https://github.com/user-attachments/assets/398fe8b9-9f14-4d55-a34b-0f7176e513b8)

After I made my account, I can now download the Windows version in the downloads tab:

The download will start, and then I'll install the VPN client. It will then have a pop-up for me to sign in with my ProtonVPN account I just made:

After I sign in, it will take me to the homepage, where I can start a VPN connection:

I'll click on "Quick Connect," and it will choose and start a VPN connection for me:

Now, if I go back to the IP address website and refresh the page, it shows me that I am in Romania instead of Canada, and I have another different IP address:

Also, while connected to the VPN, I can go to different sites like www.google.com and www.netflix.com to see the difference compared to if I were on these sites within my physical computer browser:

<h2> The Setup and Use of Proton is now Complete!</h2>

<b> We've successfully downloaded, installed, and used a free VPN called ProtonVPN! We observed the changes with our IP address and location and saw some possibilities, like accessing different content using a VPN! </b>
