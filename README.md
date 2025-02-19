<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Procedures</h2>

- Create and Log Into Virtual Machine
- Enable IIS (Internet Information Services) and Install Necesssary Software
- Register PHP Within IIS
- Enable osTicket Configurations
- Install osTicket and Enable Permissions

<h2>Installation Steps</h2>

<p>
<img src="https://i.gyazo.com/284dccfebf772ae43b4f2baf357a4256.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/67c0002f8368bb79dc0c0cd886aaf479.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
I started by setting up a virtual machine on Microsoft Azure, configuring the required specifications and settings. After the deployment was complete, I accessed the machine remotely via Remote Desktop Connection to ensure secure management and efficient operation of the environment.
</p>
<br />

<p>
<img src="https://i.gyazo.com/c88d5064db726eee86f69d22586c0cef.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/df62fee8b4f9839b2d2c73efd49138f7.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/f94065bd360a64917c098f01870d2455.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/8c73a946f2b7d1ebeb7ee4fc5129187d.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/c4f3a843f249f1e77e8ffe5e10b65ee4.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/9fb27ce4fac40a24eaa542883df3bd72.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/84ccbf7b64c1298b83f0be58fbde11cb.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
Next, I enabled IIS (Internet Information Services) to host the application and installed the required software prerequisites for osTicket, ensuring seamless integration and proper functionality.
</p>
<br />

<p>
<img src="https://i.gyazo.com/b7b345c0acd1ea943b35d223b7757201.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
Next, I registered PHP with IIS and configured the web server to recognize and process PHP as a supported scripting language, a crucial step to ensure the proper execution of PHP scripts within the system.
</p>
<br />

<p>
<img src="https://i.gyazo.com/05f43e53949ded8b21f508ffa4515d91.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/faae24f58984022e643fe00125ae71fe.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/55837ad1b062a64adc2e52cd702f343d.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
I extracted the osTicket files and verified that all essential components were properly placed and configured, ensuring smooth access to osTicket. Furthermore, I applied several recommended configurations to improve usability and optimize the system for better performance.
</p>
<br />

<p>
<img src="https://i.gyazo.com/0860af0d17c0d1a8d866ca0911540d5b.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/925b269a69866077b7e3618433fe8e18.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/aa486074c899588c982df0cf549ce5d1.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
<img src="https://i.gyazo.com/aa4d8ed4fe84f48e9fcc2d466aaa92d3.png" height="80%" width="80%" alt="osTicket Prereqs"/>
</p>
<p>
Finally, I configured the permissions and installed osTicket. Although granting full control to everyone is not advised in a production environment, I prioritized a straightforward setup for this instance to prevent potential configuration issues.
</p>
<br />
