<h1>Local Area Network Configuration</h1>

<h2>Description</h2>
Project consists of using a Windows 10 environment to execute networking commands.
<br />


<h2>Utilities Used</h2>

- <b>VirtualBox</b> 
- <b>CMD</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Local Network Configuration:</h2>
ipconfig and ipconfig /all are run to examine the differences in information given: <br/>
<img src="https://imagizer.imageshack.com/img923/5440/qBmyom.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Testing Connectivity:</h2>
Server host 10.0.0.1 is pinged. The tracert confirms this by verifying only one hop: <br/>
<img src="https://imagizer.imageshack.com/img924/8862/FHGLuc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Google's DNS is pinged (8.8.8.8). The ping includes information about the number of bytes sent and total time taken in milliseconds. Tracert confirms that there are multiple hops to reach Google's DNS: <br/>
<img src="https://imagizer.imageshack.com/img924/4900/0dMJrQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Domain Names and IPs:</h2>
The nslookup command is run to see which DNS server is configured on the machine. Nslookup is then run to find the public address of www.cisco.com. The DNS record then works in the reverse order by seeing what organization uses 185.60.216.35 (Facebook): <br/>
<img src="https://imagizer.imageshack.com/img924/5969/2b4DB2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
