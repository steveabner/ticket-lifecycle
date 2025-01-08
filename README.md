<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolve tickets within osTicket](https://www.youtube.com)

<h2>🌍 Environments and Technologies Used 🌍</h2>

- **Microsoft Azure**: Hosting virtual machines to simulate a real-world environment.
- **osTicket**: Configuring and managing the ticketing system.
- **Remote Desktop**: Accessing virtual environments for configuration tasks.
- **IIS (Internet Information Services)**: Serving as the web platform for osTicket.

<h2>🖥️ Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>🔄 Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>In this section, I will create tickets as an end user, review the ticket properties, and then respond to them as a help desk professional. I will be using both the Admin/Analyst Login Page and the End User's osTicket URL. Below are the key URLs for accessing the respective interfaces:</p>

<ul>
  <li><strong>Admin Login URL:</strong> <a href="http://localhost/osTicket/scp/login.php" target="_blank">http://localhost/osTicket/scp/login.php</a></li>
  <li><strong>User URL:</strong> <a href="http://localhost/osTicket" target="_blank">http://localhost/osTicket</a></li>
</ul>


<!--<p><strong>⬇️ Click to Expand ⬇️</strong></p>-->

<details>
  <summary>📝 Creating Tickets</summary>

- Navigate to the Support Center URL: http://localhost/osTicket, and click `Open a New Ticket`

  ![2025-01-07 15_45_22-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/772ba996-bc85-46b9-b448-4c561cc27947)

- I’ll create three tickets, entering the user’s information and detailing the issues they’re experiencing. For each ticket, I’ll select the appropriate help topic, provide a concise issue summary, add additional details, and then click `Create Ticket`.

  ![2025-01-07 16_03_29-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/37993a64-3d9e-4df0-8dca-6e7e863de04a)

   ![2025-01-07 18_23_19-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/48e94d42-2787-4a74-b157-9a4c5b42c6e6)

   ![2025-01-07 18_35_02-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/eada8d79-0042-4810-a2c5-afea85ac9dde)

</details>

# 🛠️ osTicket Workflow Demonstrations

This repository showcases the workflow for handling different ticket scenarios in osTicket, demonstrating efficient help desk management techniques. Below, you'll find step-by-step walkthroughs with visuals for each scenario.  

---

## 🎯 Table of Contents  
1. [Working a Business Critical Ticket](#working-a-business-critical-ticket)  
2. [Working a General Inquiry Ticket](#working-a-general-inquiry-ticket)  
3. [Working a Personal Computer Issue Ticket](#working-a-personal-computer-issue-ticket)  

---

### 🛠️ Working a Business Critical Ticket  

This section demonstrates how to handle tickets related to high-priority business-critical issues, such as system outages.

#### Steps:  

1. **Log In as Help Desk Agent Jane**  
   ![Agent Login](https://github.com/user-attachments/assets/e91108a1-ab6c-4682-930e-1db51f8b27c7)  

2. **View Tickets on the Dashboard**  
   Navigate to `Tickets` to see all open issues.  
   ![View Tickets](https://github.com/user-attachments/assets/983100a7-2a2e-4953-b2bb-88f1474e9737)  

3. **Review Ticket Details**  
   Open the oldest ticket and assess the `Priority`, `Department`, `SLA`, and `Assigned To`.  
   ![Ticket Details](https://github.com/user-attachments/assets/0556fd27-0301-4d25-b01e-1f1d0e4601ac)  

4. **Set Priority to Emergency**  
   Update the ticket priority from `Normal` to `Emergency`.  
   ![Update Priority](https://github.com/user-attachments/assets/bfac5371-65cf-4537-abeb-1102192258dc)  

5. **Adjust SLA and Help Topic**  
   Assign the appropriate SLA (`Sev-A`) and update the help topic to reflect the critical nature of the issue.  
   ![SLA Update](https://github.com/user-attachments/assets/35abe897-6751-49ff-92a5-cb7c538fd068)  

6. **Assign to Online Banking Team**  
   Reassign the ticket to the relevant team for resolution.  
   ![Assign Team](https://github.com/user-attachments/assets/2fbe0165-4800-465c-93aa-76aa48c06607)  

7. **Communicate and Resolve**  
   Respond to Sarah, the end-user, with updates. If resolved, mark the ticket as `Closed`.  
   ![Reply and Resolve](https://github.com/user-attachments/assets/5d9b730d-f618-4347-9961-19c42f95e528)  

---

### 🛠️ Working a General Inquiry Ticket  

This section outlines steps for addressing general support queries from users.

#### Steps:  
1. Log in as Agent Jane and access the ticket.  
2. Determine the SLA and note the issue's severity.  
3. Assign the ticket to yourself and communicate updates with the user.  
4. Resolve and close the ticket upon fixing the issue.  
![General Inquiry Workflow](https://github.com/user-attachments/assets/b93fb597-9663-405a-b4bf-54e3b9b247d0)  

---

### 🛠️ Working a Personal Computer Issue Ticket  

Handle tickets related to individual hardware or software issues.

#### Steps:  
1. Log in as Agent Jane and prioritize the ticket based on urgency.  
2. Update SLA to reflect importance (`Sev-B`).  
3. Investigate and communicate findings to the end-user.  
4. Mark the ticket as resolved upon issue resolution.  
![Personal Computer Issue](https://github.com/user-attachments/assets/ba173f78-88df-49ce-9350-6d0bed01bf85)  

---

## 🌟 Why This Project Stands Out  
This walkthrough not only highlights osTicket's functionality but also showcases real-world scenarios with a structured approach to resolution. The visuals make the process easy to follow, offering value for both beginners and professionals.  

---

### 🔗 Explore More  
Ready for the next project? Check out my [Post-Install Config Guide](https://github.com/steveabner/post-install-config) for advanced customization and setup!  

---


