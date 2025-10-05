## $${\color{hotpink}Getting \space Started \space with \space Windows \space Server \space and \space Active \space Directory}$$


### Overview
- <b>Windows Server 2025</b>, <b>Active Directory</b> and <b>Windows 11</b> will be deployed inside <b>Oracle VirtualBox VM</b>
    <ul>To keep the installation simple, default configuration will be used.
    </ul>
  

<!--------------REQUIREMENTS--------------->

<details>
<summary><b>Requirements</b></summary>
<ol><b>Oracle VirtualBox VM</b></ol>
<ol>Internet connection</ol>    
<ol>Patience</ol>
</details>
<br/>


<!--------------NOTES--------------->

<details>
<summary><b>Notes</b></summary>
<ol>This whole installation process can also be achieved with other virtualization platforms like <b>Hyper-V</b>,<br/> 
which is included as an optional feature in <b>Windows 10|11 Pro</b>, <b>Enterprise</b>, and <b>Education</b> editions.</ol>
<b>DISCLAIMER:</b><br/>
Installations in GIFs are sped up to keep them watchable.<br/>
Actual installation will require more time(+30min).
</details>
<br/>



<!--------------TABLEofCONTENTS--------------->


<details>
<summary><b><b>Table of Contents</b></b></summary> 
<ol>
<a href="#overview">Overview</a>
</ol>

<ol>
<a href="#gif1">Windows 11 ISO Aquisition »</a>
    <ul>
    <a href="#gif1.2">Installation »</a>
    </ul>
</ol>

<ol>
<a href="#gif2">Windows Server 2025 ISO Aquisition »</a>
    <ul>
    <a href="#gif3">New VM »</a><br/>
    <a href="#gif4">Boot Setup »</a><br/>
    <a href="#gif5">Installation »</a><br/>
    <a href="#gif6">New VM »</a>
    </ul>
</ol>

<ol>
<a href="#gif7">Active Directory</a>
</ol>

</details>
<br/>



<!--------------gif1--------------->
<a id="gif1"></a>
## :window: Windows 11 ISO Aquisition & Installation

<p align="center">
Launch your browser and head over to <b>Microsoft's official site</b> and download <a href="https://www.microsoft.com/en-us/software-download/windows11"><b>Windows 11 Disk Image ISO</b> for x64 device</a>: 
<br/>
<br/>
<img src="gifs/1-AD-win11isoDownload.gif" height="80%" width="80%" alt="Windows 11 download"/>
<br/><a id=""></a><br/>
</p>
<!--gif1-->

<!--gif1.2-->
<a id="gif1.2"></a>
<p align="center">
Open <b>Oracle VirtualBox VM</b> and attach the <a href="https://www.microsoft.com/en-us/software-download/windows11"><b>Windows 11 ISO</b></a> to a new virtual machine: 
<br/>
<br/>
<img src="1.2Windows 11 ISO install" height="80%" width="80%" alt="PLACE: Windows 11 iso install GIF"/>
</p>
<!--gif1.2-->

<br/>
<br/>
<br/>


<!--gif2-->
<a id="gif2"></a>
## :file_cabinet: Windows Server 2025 ISO Aquisition & Installation

<p align="center">
Head over to <a href="https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2025"><b>Microsoft's official site</b></a>, complete the registration, and download the <b>Windows Server 2025 Evaluation edition ISO for x64 devices</b>:
<br/>
<br/>
<img src="gifs/2-AD-winServer25isoDownload.gif" height="80%" width="80%" alt="WinServer25 Eval Download"/>
</p>
<!--gif2-->

<br/>
<br/>

<!--gif3-->
<a id="gif3"></a>
<p align="center">
Open <b>Oracle VirtualBox VM</b>, create a <b>new virtual machine</b>, attach the <b>Windows Server ISO</b>, and <b>allocate resources</b>: 
<br/>
<br/>
<img src="gifs/3-AD-winServer25newVM.gif" height="80%" width="80%" alt="winServer25 New VM"/>
</p>
<!--gif3-->

<br/>
<br/>

<!--gif4-->
<a id="gif4"></a>
<p align="center">
Start the new <b>Windows Server 2025 VM</b> select the ISO boot file, and complete the <b>Windows Server Setup</b>: 
<br/>
<br/>
<img src="gifs/4-AD-winServerSetup.gif" height="80%" width="80%" alt="winServer25 Setup"/>

</p>
<!--gif4-->

<br/>
<br/>

<!--gif5-->
<a id="gif5"></a>
<p align="center">
Finish installing <b>Windows Server 2025</b>: <br/>**Restart the virtual machine as many times as needed**
<br/>
<br/>
<img src="gifs/5-AD-winServerInstall.gif" height="80%" width="80%" alt="winServer25 Install"/>
</p>
<!--gif5-->

<br/>
<br/>

<!--gif6-->
<a id="gif6"></a>
<p align="center">
Once <b>Windows Server 2025</b> is installed, create a new password for the default <b>Administrator account</b> and log in: 
<br/>
<br/>
<img src="gifs/6-AD-winServerAdminSetup.gif" height="80%" width="80%" alt="winServer25 Admin Profile Setup"/>
</p>
<!--gif6-->


<h2 align="center"><b>CONGRATULATIONS</b> 🎉🎉🎉</h2>
<h4 align="center">🎊 You just installed <b>Windows Server 2025</b> 🎊<br/>
</h4>
<br/>
<br/>
<br/>



<!--gif7-->
<a id="gif7"></a>
## :card_file_box: Active Directory

<p align="center">
Install <b>Active Directory</b> by selecting the <b>Add roles and features</b> option in the <b>Server Manager</b>: 
<br/>
<br/>
<img src="gifs/7-AD-DomainSetup.gif" height="80%" width="80%" alt="winServer25 Admin Profile Setup"/>
<br/><br/>
</p>
<!--gif7-->



<!--gif8-->
### User, Group, and Object Management

<p align="center">
Log into <b>Windows Server 2025</b> and add a new <b>Organizational Unit</b>: 
<br/>
<br/>
<img src="gifs/8-AD-DomainNewAdmin.gif" height="80%" width="80%" alt="winServer25 AD newAdmin"/>
<br/><a id=""></a><br/>
</p>


<!--gif8-->



<h2 align="center"><b>🎉🎉🎉 CONGRATULATIONS</b> 🎉🎉🎉</h2>
<h4 align="center">🎊 You just Installed <b>Active Directory!</b> 🎊</b><br/><br/>
Now you are ready for some centralized management!🥳</h4>

<p align="right">(<a href="#readme-top"><strong>back to top »</strong></a>)</p>
<br/>
<br/>
<br/>
