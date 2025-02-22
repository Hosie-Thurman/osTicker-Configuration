 
![Image](https://github.com/user-attachments/assets/69d3193c-5dec-4232-ad86-5830faa00d3b)
<br />

<h1>osTicket: Post-Installation Configuration</h1>

<h2>Description</h2>
This project focuses on configuring osTicket, so it can be used properly as a ticketing system. It consists of setting up multiple agents along with their departments, roles, and permissions. As well as, configuring SLAs (Service Level Agreements), help topics, and users.<br/>
<br/>

This project is a continuation of the [osTicket: Prerequisites and Installation](https://github.com/RomainTranchant/OsTicket_Installation) project.
<br />


<h2>Environments and Utilities Used</h2>

- <b>Microsoft Azure</b>
- <b>Virtual Machines</b>
- <b>Remote Desktop Connection</b>
- <b>osTicket</b>


<h2>Operating Systems Used </h2>

- <b>Windows 10</b>

<h2>Project Walk-through:</h2>

<h3>Step 1: Log into osTicket</h3>

![Image](https://github.com/user-attachments/assets/433a0e8a-e6f0-4e82-b0d3-1b0cb948b2da)


<h3>Step 2: Checking the Registration Box</h3>


- In the Admin Panel, go to Settings.
- Navigate to the Users section.
- Find the option labeled Registration Required.
- Uncheck the box next to Registration Required to disable it.

![Image](https://github.com/user-attachments/assets/2b2e1146-d421-4222-a483-6bbe6121df7a)


<h3>Step 3: Creating Roles</h3>

- Once logged in, go to the Admin Panel.
- In the admin menu, navigate to the Agents section.
- Select Roles from the available options to manage agent roles.

![Image](https://github.com/user-attachments/assets/8d32342f-5b37-4de4-9af8-f598b365b0a6)






<h3>Step 4: Creating Roles</h3>

- In the Roles section, click the Add Role button.
- Name the new role Admin-Test.
- Navigate to the Permissions tab.
- Ensure that the appropriate boxes for permissions are checked.
- Once you've selected the necessary permissions, click Add Role to save the new role.

![Image](https://github.com/user-attachments/assets/dbc48410-6166-43c2-aa0d-543125732236)



<h3>Step 5: Creating a Department</h3>

- In the Admin Panel, go to the Departments tab.
- Click on Add New Department.
- Fill in the required details for the new department.
- Once done, click Save to add the department.

![Image](https://github.com/user-attachments/assets/51fcb730-9c03-44eb-87c7-bda17afcbf68)



<h3>Step 6: Department Details</h3>

- When adding a new department, enter the same Department Name as the previous one.
- Copy the Settings from the department level you want to replicate.
- Apply the same settings to the new department.
- After copying all settings, click Save to complete the department setup.

![Image](https://github.com/user-attachments/assets/40cb158f-9bb7-4924-88df-09a5e424e7f9)



<h3>Step 7: Log into osTicket</h3>

- In the Admin Panel, go to the Teams tab.
- Click on the Add New Team button.
- Fill in the required details for the new team.

![Image](https://github.com/user-attachments/assets/bcb0b881-a943-4ef4-ac17-e913d024e9bb)


Copy these details for there New Team 

![Image](https://github.com/user-attachments/assets/5cf10269-66d8-4ea9-bf69-59cf0b02561a)



<h3>Step 8: Creating a Agent</h3>

- In the Admin Panel, go to the Agents tab.
- Click on the Add New Agent button.
- Fill in the required details for the new agent (e.g., name, email, role).
- Once you've entered all the necessary information, click Save to add the agent.

![Image](https://github.com/user-attachments/assets/88dde7f0-8107-4277-ad26-e4e427b41f0d)

<h3>Step 9: Jane Doe details</h3>

- In the Add New Agent form, fill out the required fields (such as Name, Email, Role, etc.) exactly as shown in the screenshot.
- Once all the information is entered, click on the Set Password button.
- Follow any additional prompts to set the agent's password.
- Afterward, click Save to add the new agent with the correct details.+

  ![Image](https://github.com/user-attachments/assets/c6c34bab-4599-4c2b-af84-39c4af571b6a)

<h3>Step 10: Agent Password</h3>

- In the Add New Agent form, locate the checkbox labeled "Send the Agent a password reset email".
- Uncheck this box to disable the password reset email.
- n the Password field, type a password you can easily remember, such as Password1.
- Once you've entered the password, click Set Password to save the changes.


![Image](https://github.com/user-attachments/assets/c12ddab7-948e-4633-8bfc-c687d38e5de7)


<h3>Step 11: Agent Team details </h3>

- Navigate to the Access tab.
- Copy the settings shown there (either manually or by ensuring the same configurations are applied as in the previous department or team setup).
- After copying the settings, go to the Teams tab.
- Select the team you created earlier.
- Add Jane to the team by either selecting her from a list of agents or typing her name into the provided field.
- Once done, click Save to add Jane to the team.

![Image](https://github.com/user-attachments/assets/26008804-8aee-466b-87a3-910ec0795dd0)

<h3>Step 12: Creating another Agent</h3>

- Follow the same process to Add New Agent.
- Fill out the details for John Doe.
- In the Password field, enter the same password you used for Jane (e.g., Password1).
- Uncheck the box that says "Send the Agent a password reset email".
- After entering the password, click Set Password.
- Now, navigate to the Departments section and set John Doe's department to Limited Access in the Support section.
- After configuring everything, click Save to add John Doe with the correct settings.

![Image](https://github.com/user-attachments/assets/c096a63b-bd76-424c-859c-05fe6726e4d9)

<h3>Step 13: Adding SLA Plans</h3>

Here are the steps to add the SLAs:

- In the Admin Panel, go to the Manage section.
- Select SLA from the available options.
- Click on the Add New SLA Plan button.
For each SLA plan, fill out the details as follows:
* SEV-A:
    * Grace Period: 1 hour
    * Schedule: 24/7
    * Click Save.
* SEV-B:
    * Grace Period: 4 hours
    * Schedule: 24/7
    * Click Save.
* SEV-C:
    * Grace Period: 8 hours
    * Schedule: Business Hours
    * Click Save.

![Image](https://github.com/user-attachments/assets/d5ab2dab-fc67-4900-bdc1-237620e2e5a0)


<h3>Step 14: Adding Help Topics</h3>

In the Admin Panel, go to the Manage section.
Select Help Topics from the available options.
Click on the Add New Help Topic button.

Enter the following help topics one by one:
* Business Critical Outage
* Personal Computer Issues
* Equipment Request
* Password Reset
* Other
After entering each help topic, click Save to add it.

![Image](https://github.com/user-attachments/assets/48f623a8-c4b7-4725-90e6-4953f59bb2d6)


<h3>Step 15: Creating a User</h3>

- In the Admin Panel, navigate to the Agent Panel.
- Once in the Agent Panel, look for the option to add a new user (this might be labeled as Add New User or something similar).
- Proceed to fill in the required information to create your first user.

![Image](https://github.com/user-attachments/assets/580f337b-6c01-43fc-8c7a-be9d1fd56e4b)


<h3>Step 16: User Details</h3>

In the Admin Panel, go to Users.
Select User Directory.
Click on Add User.
Copy the following information into the respective fields:
* Email: UserTest@gmail.com
* Full Name: User Test
Once the information is entered, Add User to create the new user.

![Image](https://github.com/user-attachments/assets/847c3627-6712-4a2b-80ec-4138cbeda549)



<b> We've successfully set up multiple agents along with their departments, roles, and permissions. As well as, configured SLAs (Service Level Agreements), help topics, and users! osTicket is now setup for the next project where I will create and work different tickets using multiple agents and users!  </b>
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
