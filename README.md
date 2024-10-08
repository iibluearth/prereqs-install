# prereqs-install
<p align="center">
<img src="https://i.imgur.com/vJThaBx.png" alt="osTicket logo"/>
</p>

 <h2>Environments and Technologies Used</h2>

 - Microsoft Azure (Virtual Machines/Compute)
 - Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Account
- Windows 10

 <h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/3dz4Weq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Start Free Azure Account:

Go to azure.microsoft.com/en-us/free and click "Start free."
</p>
<br />

<p>
<img src="https://i.imgur.com/AjvEYJO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Account Setup:

Fill in your info and add your credit/debit card details.
New users get $200 free credit for 30 days.
</p>
<br />

<p>
<img src="https://i.imgur.com/9ocZ89o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Navigate to Virtual Machines:

In the search bar, type "Virtual machines".
</p>
<br />

<p>
<img src="https://i.imgur.com/yhmYcHf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Create Virtual Machine:

Click "Create" and then "Azure virtual machine."
</p>
<br />

<p>
<img src="https://i.imgur.com/w650FkZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/tZyVFaL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
5. Configure Virtual Machine:

- Choose "Create new" for Resource group and name it RG-Test.
- Name your Virtual machine VM-1.
- Select "Windows 10 Pro, version 22H2" for Image.
- Choose a Size, like Standard_B4ms (4vcpus, 16 GiB memory).
- Set Username as "labuser" and Password as "Labpassword123."
- Check the box for Licensing.
- Keep other settings default, note your Region.
- Click "Review + create."
</p>
<br />

<p>
<img src="https://i.imgur.com/MnWi05f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Create VM:

Wait for validation to pass, then click "Create."
</p>
<br />

<p>
<img src="https://i.imgur.com/0cuquBN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Wait for Deployment:

Wait until you see "Your deployment is complete."
</p>
<br />

<p>
<img src="https://i.imgur.com/3eff9uv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Access VM:

Click "Go to resource" to see your VM's info.
Copy the "Public IP address."
</p>
<br />

<p>
<img src="https://i.imgur.com/LqbvG6j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/7nsTPor.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/MRFIuFI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <img src="https://i.imgur.com/E9NtnS7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
9. Remote Desktop Connection:

- Open "Remote Desktop Connection" from the Windows search bar.
- Paste the IP address and click "Connect."
- Enter the credentials: Username: labuser, Password: Labpassword123.
- Click "Yes" on the certificate prompt.

</p>
<br />

<p>
<img src="https://i.imgur.com/LQln2z1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
10. Whoop-whoop!

You're now inside your virtual machine.
</p>
<br />
