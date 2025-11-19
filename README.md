<img width="700" height="200" alt="Osticket" src="https://github.com/user-attachments/assets/9ed56504-197e-4d83-8473-ad9addd88a89" />

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system, osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)</b> (21H2)

<h2>Configuration Steps</h2>

<img width="961" height="507" alt="OS POST 1" src="https://github.com/user-attachments/assets/b73723f5-50fe-40d5-ad34-7e6faf33c4ed" />
<P>
  
</P>
Great! Now that osTicket is successfully configured, we will proceed with system administration tasks, starting with configuring new roles within the help desk. This will allow you to manage user access and permissions effectively.
<P>
  
</P>
<img width="963" height="441" alt="OS POST 2" src="https://github.com/user-attachments/assets/4acdfc20-96e5-49e1-9210-54415511a502" />
<P>
  
</P>
To configure new roles within the help desk, go to the Admin Panel -> Agents -> Roles. Click on "Add new role" and enter the name of the new role, such as Supreme Admin. This will allow you to define the permissions and responsibilities for the role. Since you are creating a Supreme Admin role, this role will be granted all permissions. Ensure all available permissions are selected for this role to provide full administrative access.
<P>
  
</P>
<img width="1028" height="968" alt="OS POST 3" src="https://github.com/user-attachments/assets/68f5a43b-b853-4cc2-93ee-f602206c9f6f" />
<P>
  
</P>


Select the "Departments" button in the Agents tab. Here, you can create a new department, with each agent assigned to a specific department based on their role within the help desk. Create a department named "System Administrators", which will serve as the designated department for Supreme Admins. Additional settings, such as SLAs, managers, and email configurations, can be customized within the Departments tab to align with your help desk's operational needs.
<P>
  
</P>
<img width="964" height="709" alt="OS POST 4" src="https://github.com/user-attachments/assets/8c4dbf7d-7e33-4d93-adbc-70f61dc20fd8" />
<P>
  
</P>


To configure teams, navigate to Admin Panel -> Agents -> Teams. Teams allow you to group agents from different departments to collaborate effectively. Create a team named Level II Support and assign agents from various departments as needed.
<P>
  
</P>
<img width="962" height="713" alt="OS POST 5" src="https://github.com/user-attachments/assets/98716214-0e03-46cb-987a-d40293c9f2ab" />
<P>
  
</P>
To allow anyone to create tickets, go to Admin Panel -> Settings -> User Settings. Uncheck the option "Require registration and login to create tickets" to enable unregistered users to submit tickets without needing an account.
<P>
  
</P>
<img width="973" height="965" alt="OS POST 6" src="https://github.com/user-attachments/assets/8e4cf85b-58da-480a-a864-69ffb4ec66c3" />
<P>
  
</P>
To configure agents (workers), go to Admin Panel -> Agents -> Add New. Fill in the necessary details, such as the agent's name, email, assigned role, and department, to set up their profile and permissions.
<P>
  
</P>
<img width="960" height="691" alt="OS POST 7" src="https://github.com/user-attachments/assets/d9e6e212-cedf-4b4e-b926-29330015877d" />
<P>
  
</P>
To configure users (customers), go to Agent Panel -> Users -> Add New. Add users such as Ryu and Ken by entering their details, including names and email addresses, to enable them to submit and manage their tickets.
<P>
  
</P>


<img width="954" height="659" alt="OS POST 8" src="https://github.com/user-attachments/assets/28d3a1b2-9493-4757-b44d-2521c0eb967a" />
To configure help topics for user ticket creation, navigate to Admin Panel -> Manage -> Help Topics. These topics will guide users in categorizing their tickets effectively.
