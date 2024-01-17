
<h1> Remnux Setup</h1>

 

<h2>Description</h2>
These are the steps needed to setup your remnux machine. We will go step by step so that we can have an intercepting proxy utlizing burpsuite. This will allow us to detonate malware on a sandboxed system without compromising any systems but still monitor. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> 
- <b>Oracle Virtual Machines</b>
- <b>Burpsuite</b>
- <b>Inetsim</b>
- <b>YAML</b>

<h2>Environments Used </h2>

- <b>Linux</b>
- <b>Remnux</b>

<h2>Program walk-through:</h2>

<p align="center">
 The first step we need to take is going to the website to download the remnux OVA file (Please note this is done on host machine):
 <br/>
<img src="https://i.imgur.com/ODjUW7F.png" height="" width="60%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Next step is we find the file in downloads and double click the file:  <br/>
<img src="https://i.imgur.com/aO0cYHS.jpeg" height="80%" width="60%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
There will be a prompt window, we will setup our VM with default settings and click "Next/Finish":  <br/>
<img src="https://i.imgur.com/c0GmQqe.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Now we need to open up the terminal and get our updates for Remnux by using the ap-get update command.<br/> We are using Sudo before the command because we are not in root. :  <br/>
<img src="https://i.imgur.com/zNjEiyh.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />












</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

