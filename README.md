<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
The tutorial explains you the post installation setup and configuration of osTicket.<br />





<h2> Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)






<h2>Configuration Steps</h2>


The osTicket has two panels

1. Admin Panel

2. Agent panel

You can switch back and forth between these two panels

We will start configuration process with admin panel






Your admin panel should look like the image below 

<p>
<img src="https://i.imgur.com/bD3uxih.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>



In the admin panel go to Agents >Roles

</p>
<br />

<p>
<img src="https://i.imgur.com/QiZMLfA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Add new role and name it "Supreme Admin"

Go to Permissons and allow permissions for everything in each section of the Permissions menu

Save changes after you set the permissions



</p>
<br />

<p>
<img src="https://i.imgur.com/2oWgIPQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>




Now go to Agent >Departments and add a new department

Name it as "System Administrators"

Click on "Create Dept" on the bottom




</p>
<br />

<p>
<img src="https://i.imgur.com/V1rSb5K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>



Next go to Agent >Teams

Create a new team and name it "Level 2 Support" and click on "Create Team" 


</p>
<br />

<p>
<img src="https://i.imgur.com/oQ9Ebo8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>




Next , allow everyone to create tickets

In the Admin Panel go to Setting >Users

Select "Require registration and login to create tickets" and then "Save Changes"


</p>
<br />

<p>
<img src="https://i.imgur.com/g9BRi5l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>



</p>
<br />

<p>
<img src="https://i.imgur.com/CHRIj4X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>



Configure Agents 

Go to Admin Panel >Agents >Add New

1.Jane DOE



</p>
<br />

<p>
<img src="https://i.imgur.com/e98hgB7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Set the Password

</p>
<br />

<p>
<img src="https://i.imgur.com/zs8OFVE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Give Access



</p>
<br />

<p>
<img src="https://i.imgur.com/PK7hO3q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


2. John Doe



</p>
<br />

<p>
<img src="https://i.imgur.com/mJQ95Zy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Set Password


</p>
<br />

<p>
<img src="https://i.imgur.com/81UczDo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Give Access




</p>
<br />

<p>
<img src="https://i.imgur.com/1wUeAiF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>




Next Configure Users

Switch to Agent Panel and then go to Users >Add User

Add two users in the User Directory

1. Karen

2. Ken



</p>
<br />

<p>
<img src="https://i.imgur.com/nvfVOqf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Next Configure SLA

Switch back to Admin Panel and go to Manage <SLA

Set the SLA as follows

1. Sev-A (1 hour, 24/7)
2. Sev-B (4 hours, 24/7)
3. Sev-C (8 hours, business hours)



</p>
<br />

<p>
<img src="https://i.imgur.com/fNGmxfp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>




</p>
<br />

<p>
<img src="https://i.imgur.com/WUO03JW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>



Finally the last step is to configure Help Topics

Go to Admin Panel >Manage >Help Topics





















