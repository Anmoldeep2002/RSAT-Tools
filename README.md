<h1>Installing Active Directory on Helpdesk Account (RSAT Tools)</h1>


<h2>Description</h2>
<p>In this section, I will install Active Directory on the Helpdesk account for the Helpdesk employee. This will also allow him to manage users and services.</p>


<br />

<h2>Step-by-Step Walk-Through:</h2>


<p align="center"> 
STEP 1: <br/>
<img src="https://i.imgur.com/quMVi4a.png" height="70%" width="70%"/> </p>


<p align="center">The server manager is not permitted for a Level 1 help desk. As a result, RSAT tools must be installed on the Windows 10 device in order to access the server manager's critical functions, such as Active Directory users and computers. I'll be able to manage users and computers through the "DOMAIN CONTROLLER" without having to log in to a server. 
To activate RSAT tools, I started by searching for the "ADD AN OPTIONAL FEATURE" function. I then clicked on that feature to access other settings.


</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 2: <br/>
<img src="https://i.imgur.com/RxYnnlW.png" height="70%" width="70%"/> </p>


<p align="center">From here, I choose "ADD A FEATURE" to access more options, such as RSAT tools.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 3: <br/>
<img src="https://i.imgur.com/kfuWU35.png" height="70%" width="70%"/> </p>


<p align="center">From here, I can finally look for the tools I need for RSAT. In this scenario, I've chosen a number of RSAT features to include on the Windows 10 device. I checked and selected all of the features required for this device, then clicked "INSTALL" to begin installing them.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/t1AFPf3.png" height="70%" width="70%"/> </p>


<p align="center">The RSAT tools have been successfully installed, as shown in the image above. I now need to restart the device to ensure that they appear on the device's menu screen.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/M5LQxDG.png" height="70%" width="70%"/> </p>


<p align="center">As you can see, "ACTIVE DIRECTORY USERS AND COMPUTERS" has been successfully installed, along with many other features. I've also opened it to see whether it works, but the device isn't connected to a domain, so I can't manage any users or computers for now.</p>


<a href="https://www.example.com">
  <button>NEXT</button>
</a>
