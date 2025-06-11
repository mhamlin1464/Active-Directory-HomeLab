<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
This project simulates an enterprise Active Directory environment using Oracle VirtualBox, Windows Server 2019, and Windows 10 Pro. It covers user authentication, OUs, domain controller setup, and basic network management. 
<br />


<h2>Technologies Used</h2>

- <b>Oracle Virtual Box</b> 
- <b>Window 2019 Server ISO</b>
- <b>Window 10 Pro</b>

<h2>HomeLab walk-through:</h2>

<p align="center">
 Creating 2019 Windows Server: <br/>
<img src="https://github.com/user-attachments/assets/a9cb2507-d3fb-4123-a5f9-a15957c84bf4"/>
<br />
<br />
 Windows Server Setup:  <br/>
<img src="https://github.com/user-attachments/assets/998a5302-6290-4d5b-acec-b62b2f9058aa"/>
<br />
<br />
Determined the internet adapter and the intranet adapter: <br/>
<img src="https://github.com/user-attachments/assets/80007ac4-ead9-4705-ac1e-92a5c727c8e7"/>
<br />
<br />
Assigned IP Configuration to the Internal Network:  <br/>
<img src="https://github.com/user-attachments/assets/df1ea53f-2816-4e4d-aa98-a9ce95cb0222"/>
<br />
<br />
Installing AD to the Server:  <br/>
<img src="https://github.com/user-attachments/assets/fbcce7a7-9037-4419-a663-403e6b718fef"/>
<br />
<br />
Created an Admin OU:  <br/>
<img src="https://github.com/user-attachments/assets/61362ab7-03f5-4788-8b16-b2da689e3a1b"/>
<br />
<br />
Crreating a New User in our Admin OU:  <br/>
<img src="https://github.com/user-attachments/assets/e9343bc9-7de3-4f38-8e5c-0d408d5830db"/>
<br />
<br />
Making the User Apart of the Dmain Admins Group: <br/>
<img src = "https://github.com/user-attachments/assets/8e371718-065d-43d9-89be-bb5b691407eb"/>
<br />
<br />
Installing Routing and Remote access so that clients can communiate with server and internet: </b>
<img src = "https://github.com/user-attachments/assets/942ce9c1-89f9-496b-b9e2-d8e7299a4154" />
<br />
<br />
Configuring Routing and Remote Access to use our Internet NIC: </b>
<img src = "https://github.com/user-attachments/assets/76ca075d-be9e-4d62-8648-9137240dae83" />
<br />
<br />
Installing a DHCP Server: </b>
<img src = "https://github.com/user-attachments/assets/8efb2d55-342b-4a94-ad2d-0c2d4a691ef6" />
<br />
<br />
Adding a Scope of IP Addresses to the DHCP Server: </b>
<img src = "https://github.com/user-attachments/assets/341a2d39-5b91-48fa-9066-fad182efcd24" />
<br />
<br />
Running a Script to create 1000 sample users: </b>
<img src = "https://github.com/user-attachments/assets/e0eb3aa9-a8fd-4325-be4b-0a6a4e5ce6e0" />
<br />
<br />
Creating a Dummy Windows 10 Client: </b>
<img src = "https://github.com/user-attachments/assets/611edce2-a056-4b96-9ff4-c9e190387b70" />
<br />
<br />
Client is connected to our network: </b>
<img src = "https://github.com/user-attachments/assets/c205692c-d578-4662-9f13-57dd18d4e058" />
<br />
<br />
Client Has Internet! : </b>
<img src = "https://github.com/user-attachments/assets/d0b77c9e-7325-49ae-b00a-d9e804323325" />
<br />
<br />
CLIENT1 has an IP lease : </b>
<img src = "https://github.com/user-attachments/assets/54db0a3f-009c-488c-9f2a-168cfdad2dd7" />
<br />
<br />
CLIENT1 is a member of the domain : </b>
<img src = "https://github.com/user-attachments/assets/9927e598-307c-4aaf-8ed4-7c9ef39290b8" />
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
