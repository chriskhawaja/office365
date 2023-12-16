

![image](https://github.com/chriskhawaja/office365/assets/153021794/90655e7d-c11a-4df6-beae-c2ac8404423a)






<h1>Practicing Administrative Roles and Actions within Office 365</h1>

<h2>Project Summary</h2>
This project involves the installation of the Microsoft Office 365 Developer Program, which gives the user administrative access to Office 365 for 90 days. After installing Office 365 Developer, the user will have administrative control over 16 fictitious users in a workplace scenario. Accessing the administrative section of Office 365 will show us how to reset passwords, block sign-ins, create and delete users, share mailboxes, add groups and distribution lists, trace messages through Exchange, and restore deleted emails via Sharepoint. Learning all of the described administrative features is essential, as Office 365 is heavily utilized in many IT environments. The completion of this project should prepare individuals with the basic fundamentals of Office 365. Thus, when faced with Office 365 troubleshooting scenarios, the individual should have some familiarity in using the Office 365 administrative platform.
<h2>Platforms and Technologies Used</h2>

- Microsoft Office 365 Developer Program
- Creation of a Microsoft Account
- Microsoft 365 Admin Center
- Microsoft Exchange
- Microsoft Sharepoint
- Microsoft Intune Admin Center
<h2>Operating Systems Used </h2>

- Windows 11

<h2>Project Installation Steps</h2>

- Step 1
  - Search on Google "Microsoft 365 Developer Program" and click the first link
![image](https://github.com/chriskhawaja/office365/assets/153021794/090fc3b6-5b13-43cf-bdad-a3d4955cab51)


- Step 2  
  - Click the "Join Now" button once you reach the website
 ![image](https://github.com/chriskhawaja/office365/assets/153021794/43b7c9de-01ea-4fb3-8fcf-aa42e3ff3355)


- Step 3
  - Sign-in with your Microsoft Account
  - Create an account if you don't have one
    
![image](https://github.com/chriskhawaja/office365/assets/153021794/7b500a22-230d-4755-9be3-000d1333a807)




- Step 4
  - Fill out the required information
  - Select "Personal projects" for your primary focus as a developer
  - Check all the boxes and select "Save"

![image](https://github.com/chriskhawaja/office365/assets/153021794/99852d11-b8ab-4bb9-b7a4-10268acc6f18)
![image](https://github.com/chriskhawaja/office365/assets/153021794/d1088c97-fcf9-47c7-9d9e-331f72506c49)
![image](https://github.com/chriskhawaja/office365/assets/153021794/13361555-31d8-49a7-89b0-5158603fe023)



- Step 5
  - Select "Instant sandbox", which builds the Microsoft Office 365 environment for us, along with the 16 fictitious users
  - Take note of the 90 days we have to use the subscription, as well as our domain name on the right
   ![image](https://github.com/chriskhawaja/office365/assets/153021794/1016d1b6-42d6-490f-bc5b-0d6322914a78)


- Step 6
  - Create your admin username and password
  - Create an alternative password for the 16 fictitious users
  - You will be prompted to enter in a phone number for security purposes
    - Enter a phone number and the Developer Environment should begin the setup process
  - Select "Go to subscription" to access the environment 
  ![image](https://github.com/chriskhawaja/office365/assets/153021794/734639b2-3015-4912-bb31-c1736ef4664f)

   

- Step 7
  - From there, you should see your administrator username and your assigned domain name
  - Enter the password that your created for your admin account and click "Sign-in"
  - Select "Ask later" when it comes to the security question
    
![image](https://github.com/chriskhawaja/office365/assets/153021794/08511636-24e8-4652-9d9c-bf03b6656416)


- Step 8
  - You should now be in your Microsoft Office 365 environment
  - To access the Admin controls, click the 3 rows of dots in the top left corner
  - Under Apps, select "Admin"
  - ![image](https://github.com/chriskhawaja/office365/assets/153021794/2fff29cd-327a-4ce1-8bff-3360eb0e644a)
  - ![image](https://github.com/chriskhawaja/office365/assets/153021794/34a3d601-a8c5-497e-b67a-98c3bc4c3117)
 
- Step 9
  - You have now successfully installed the Microsoft 365 Developer Program and have access to the Administrative Center
  ![image](https://github.com/chriskhawaja/office365/assets/153021794/4b7944ff-388a-420e-8d5e-231393706cc5)


<h2>Project Demonstration</h2>

<p>

![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/0671b969-85bd-41ab-bcf3-0f04519b67ac)
  - We can see there is a connection established between VM1 and VM2 via the non-stop ping command
    - ping 10.0.0.5 -t
      - This command can be entered into command prompt by typing "cmd" in the start menu below
        - Make sure that before clicking cmd, right-click and select "run as administrator"
- 10.0.0.5 is the private IP Address of our Linux Virtual Machine

![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/aecc41e7-943b-488c-91b5-9365e1bfb142)
- We will now block this connection by going back to Microsoft Azure, and typing in "Network Security Groups" into the search bar
- On the left, we can click the "Inbound Security Rules" tab, and click the add button - this tab is selected because we want to block any ICMP traffic coming into VM2, hence the word "inbound"
- Be sure to select ICMP as the protocol and the deny option
  - ICMP stands for Internet Control Message Protocol, and is the protocol that is used when using the ping command
- Lastly, select the add button, and the security rule will be created

![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/ca61784b-48d5-4c3d-86fc-db57538c90a9)
- Now, we can observe that any traffic being sent to VM2 is being blocked

  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/25ae8002-6238-4782-bf84-f59863d0d4a3)
- We can reverse this process by going back to our NSG for VM2, selecting the rule we created, and clicking the allow button under ICMP
- Be sure to press "save" and the rule will be created

  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/7d98f982-45f0-4928-8eb8-1af9450b4d3b)
- We can see the replies from VM2 coming back after we changed the inbound rule 

![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/dcaf8831-58c9-4eee-8774-a0f187424535)
- Utilizing SSH, we can also acces the Linux terminal of VM2 from VM1
  - To access VM2 using VM1, be sure to input SSH Username@IP Address
    - The username and IP address of the VM that you are trying to access
   
![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/dcec2035-05ec-472a-8a8f-12645b2a06fc)
- Once we filter for Remote Desktop Protocol traffic, we can see the inundation of traffic
  - This is because we are literally using RDP to access our VM
 
  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/20ff0139-ebf7-4af2-b4e8-7e5ab8ac5f94)
- After visiting different websites on our VM, we can see all the DNS information on Wireshark
- Additionally after utilizing the command "ipconfig /displaydns", we can see that our cache is full of information

  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/4f6a5650-6f0a-46c3-ba8b-602a661b59c9)
- To flush our DNS cache, we can use the "ipconfig /flushdns" command
  - This command is really important when users are experiencing a multitude of DNS issues
 
![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/67e1cf2c-17f3-4859-8201-12f1d177169b)
- To view our DHCP and DNS servers, we can type the command "ipconfig /all" into command prompt

  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/e20a6d00-e5f7-4516-9a66-daf11afcfbaf)
- DHCP traffic can be analyzed by using the "ipconfig /release" and "ipconfig /renew" commands
  - The release command will tell our DHCP server to get rid of our current IP address, which was given to us via DHCP
  - The renew command will give us a new allocated IP address that is dynamically given via DHCP
  - Note that when you use these commands, your connection may be lost since we have "released" the VM's current IP address
 
  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/cad81990-28a6-4ddd-aea6-5eee091ed677)
  - You can now see in Wireshark, the steps of DHCP release and renewal
    - The DORA process highlights how a Client and DHCP Server communicate
      - Discovery, Offer, Request, and Acknowledge 
      
