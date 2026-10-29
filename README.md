<h1>Setting Up Attacker VM /Kali Linux </h1>


<h2>Description</h2>
A practical, step-by-step guide to installing, configuring, and preparing Kali Linux as a penetration testing attacker machine in Oracle VirtualBox. Covers virtual machine setup, network configuration, post-installation setup, essential security tools, verification, troubleshooting, and lab documentation for cybersecurity learners.
<br />


<h2>Utilities Used</h2>

- <b>Browser .ex; Google chrome</b> 
- <b>Virtualbox</b>
- <b>Kali Linux ISO</b>


<h2>Environments Used </h2>

- <b>lightdm</b> 

<h2>Program walk-through:</h2>

<p align="center">
the procedure to create the  vm is to open an app ,I’m showing virtualbox:
first click new than add things: <br/>
<img width="889" height="623" alt="image" src="https://github.com/user-attachments/assets/979e54c5-43d0-4623-b7a0-f56fe73813f8" />

<br />
<br />
Next you’ll be shown your ram ,storage & processor allocation keep it within your device range .Keep it while your device configuration.Than click on the start machine option:  <br/>
<img width="644" height="558" alt="image" src="https://github.com/user-attachments/assets/b7510658-69e2-49c2-b93b-697261910164" />
<br />
Follow Steps in the given order.  <br/>

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/b5d2686a-25f0-4c53-b852-60dff5e7c150" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/61a46b71-55da-4e98-b1b0-2ddd31964521" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/63bb6c58-1003-4294-b74e-04b934c9743c" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/d0586759-254d-454a-b25e-ec8112bf84e3" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/af5272cd-3289-4d0f-a229-2ca4e67d0047" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/ca88484b-a9f7-4e5e-a6bf-d497d2c310bd" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/e927f5c2-65a2-4d2b-9c83-65fd052edcd0" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/3a142226-c2f5-45c5-af83-4ebe9fb66b7e" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/eb8b92d0-6970-44e8-bbb6-ecb229dc153c" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/6c194fb0-22bc-4d95-9ec0-c84833e40706" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/9226a952-59f5-4a31-9ba4-e5cc1833a709" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/87acf9af-300b-47f9-a3ee-7abaee3aa635" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/01d04eb0-a27b-4687-b613-f2d4f31258f0" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/f2adf381-88c7-405f-8784-a7b85d6216b0" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/c4431cdb-4b97-49f9-aeb4-ca50154ecb2e" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/17b57bba-c01c-4c32-b4b9-58f6cec08132" />

<br />
Next the base system will install just like this : <br/>

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/d76ae86a-944f-4524-a44c-82fa5d61bcef" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/89a902a6-ad79-4bce-96ed-80580881feed" />

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/2148203d-77b8-4975-9dd8-bee52f100d00" />
<br />
after selecting it will auto download and install:
 <br/>

<img width="802" height="671" alt="image" src="https://github.com/user-attachments/assets/9c224e76-9cb4-4cbf-af91-035a9f4d093a" />

<br/>
once it is done it will automatically install grub bootloader & ask for reboot.
<br/>
<img width="809" height="679" alt="image" src="https://github.com/user-attachments/assets/362df438-93c9-4bcd-90fc-1f994e3b8ce9" />



<img width="809" height="679" alt="image" src="https://github.com/user-attachments/assets/ef8f0db3-dc03-4834-8ac0-55b2a2e4c30c" />

<img width="809" height="679" alt="image" src="https://github.com/user-attachments/assets/057427ce-5790-4cb6-9d39-6ac45cfdd3ce" />

<br/>
Just press reboot.
than It’ll reboot and start automatically .After that close it .

now for network setup:
goto file→tools→network→ NAT networks and do configuration like this manually.
<br/>
<img width="970" height="936" alt="image" src="https://github.com/user-attachments/assets/673f11d0-cb83-4a53-8953-fc188c736bf6" />
<br/> Then Start Attacker VM machine / Kali <br/>
<img width="1281" height="851" alt="image" src="https://github.com/user-attachments/assets/c54e9bb1-4c06-479a-96fc-ab4104707a1a" />
<br/> To finallly check if configured network Is working on VM <br/>
<img width="1281" height="851" alt="image" src="https://github.com/user-attachments/assets/c3f9c703-e6a4-4567-bc57-4f720375540c" />



</p>

<h3 align="center">Thus the machine can be used with full configuration!!</h3>
