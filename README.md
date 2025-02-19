<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">🎫 osTicket - Ticket Lifecycle: Intake Through Resolution 🎫</h1>
<p align="center">
  This project outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system, osTicket.
</p>

---

<!--<h2 align="center">📽️ Video Demonstration 📽️</h2>

<p align="center">
  ▶️ <a href="https://www.youtube.com">Watch on YouTube: How to create, work, and resolve tickets within osTicket</a> ◀️
</p>

---
-->
<h2>🌍 Environments and Technologies Used</h2>

| **Technology**        | **Purpose**                                   |
|------------------------|-----------------------------------------------|
| **Microsoft Azure**    | Hosting virtual machines for simulation.     |
| **osTicket**           | Configuring and managing the ticket system.  |
| **Remote Desktop**     | Accessing virtual environments.              |
| **IIS**                | Serving as the web platform for osTicket.    |

<h2>🖥️ Operating Systems Used</h2>

- **Windows 10 (21H2)**

---

<h2>🔄 Ticket Lifecycle Stages</h2>

1. **Intake**  
2. **Assignment and Communication**  
3. **Working the Issue**  
4. **Resolution**  

---

<h2>📝 Lifecycle Stages</h2>

In this section, I’ll demonstrate the process of creating, assigning, and resolving tickets using both the Admin/Analyst Login Page and the End User's osTicket URL.

- **Admin Login URL**: [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)  
- **User URL**: [http://localhost/osTicket](http://localhost/osTicket)  

---

<details>
  <summary>📝 Creating Tickets</summary>

- Navigate to the Support Center URL: http://localhost/osTicket, and click `Open a New Ticket`

  ![2025-01-07 15_45_22-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/772ba996-bc85-46b9-b448-4c561cc27947)

- I’ll create three tickets, entering the user’s information and detailing the issues they’re experiencing. For each ticket, I’ll select the appropriate help topic, provide a concise issue summary, add additional details, and then click `Create Ticket`.

  ![2025-01-07 16_03_29-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/37993a64-3d9e-4df0-8dca-6e7e863de04a)

   ![2025-01-07 18_23_19-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/48e94d42-2787-4a74-b157-9a4c5b42c6e6)

   ![2025-01-07 18_35_02-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/eada8d79-0042-4810-a2c5-afea85ac9dde)

</details>

<details>
  <summary>🛠️ Working a Business Critical Ticket</summary>

- I'll log in as Agent Jane.

  ![2025-01-07 16_34_46-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/e91108a1-ab6c-4682-930e-1db51f8b27c7)

- On the dashboard, I’ll navigate to Tickets to access the list of all newly created tickets.

 ![2025-01-07 18_37_53-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/983100a7-2a2e-4953-b2bb-88f1474e9737)

- I'll begin with the oldest ticket and work my way to the newest. Starting with the online banking ticket, I'll open it and review its `Priority`, `Department`, `SLA`, and `Assigned To` details.

  ![2025-01-07 18_42_32-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/0556fd27-0301-4d25-b01e-1f1d0e4601ac)

- Since the online banking system is completely down, I’ll update the priority to `Emergency`. To do this, I’ll click on `Normal`, select `Emergency`, and then click `Update`.

  ![2025-01-07 19_12_05-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/bfac5371-65cf-4537-abeb-1102192258dc)
  ![2025-01-07 19_13_29-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/6bfdf75d-bfc6-4bc1-9685-b541a0c938b0)

- Next, I'll set the SLA. To do this, click `Default SLA`. I'll select `Sev-A`, add a note, then click `Update`.

  ![2025-01-07 19_41_23-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/35abe897-6751-49ff-92a5-cb7c538fd068)

  ![2025-01-07 19_56_18-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/25c24da8-5c97-4152-8c9d-c9ef113a4124)

- I'll change the help topic to reflect a critical issue. Click `Report a Problem`, change it to `Business Critical Outage`, add a note, then click `Update`.

  ![2025-01-07 19_59_42-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/a2109d98-3b89-45b9-b172-bf096cb113d3)
  ![2025-01-07 20_01_07-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/ac379d45-14ae-4e1c-b8ff-df45280565af)

- Now I'll assign the ticket to the appropriate online banking team, I'll click `Unassigned`, select `Online Banking`, then click `Assign`.

  ![2025-01-07 20_04_38-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/2fbe0165-4800-465c-93aa-76aa48c06607)
  ![2025-01-07 20_07_05-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/bf1f25c2-ee5a-49c8-b31d-679cbc0e3e16)

- Next, I’ll log in as Agent John and continue working on the ticket until it’s resolved.

  ![2025-01-07 22_42_47-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/ed95187b-18ec-42d0-a76e-b5ab43a9c8eb)

- First, I'll assign the ticket to `John Smith`. 

  ![2025-01-07 22_44_49-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/418dd717-5378-4782-a014-e78db292c819)

  ![2025-01-07 22_45_27-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/f323fb91-7e8e-483b-9181-5ae04ca98a68)

- Next, I'll respond to Sarah, reassuring them that we're actively investigating the outage issue.

  ![2025-01-07 22_52_43-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/93b72fc2-b99b-4b70-8694-14f54105839e)

- Finally, if a solution is found, I'll update Sarah on our findings, and close the ticket.

  ![2025-01-07 22_58_56-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/5d9b730d-f618-4347-9961-19c42f95e528)

- To resolve the ticket, I'll find `Status` then click `Open`, change it to `Resolved`, then click `Close`

  ![2025-01-07 23_01_39-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/78c4bf85-db15-489b-8459-c62a9b525266)
  ![2025-01-07 23_03_40-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/bdbeb30a-cc3b-43c4-8b0d-0cd1a727d767)

</details>

<details>
  <summary>🛠️ Working a General Inquiry Ticket</summary>

- In this section, I'll log in as Agent Jane, and work on the ticket from the accounting department.

  ![2025-01-07 23_26_13-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/d5d723de-b9c4-4eec-8cd7-6e785aa05707)

- I'll open and examine the ticket. It looks like the accounting department is having issues with Adobe.

  ![2025-01-07 23_29_16-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/7419ac2c-4585-4e07-b293-9d0761ebe89f)

- When encountering an issue like this, it’s often helpful to contact the customer directly for more details. For this lab, let’s assume that after speaking with Karen over the phone, we determined that only two people in accounting are experiencing the problem. Since this isn't a business-critical issue, I’ll set the SLA to `Sev-C` and document our conversation in the notes.

  ![2025-01-07 23_35_33-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/93174951-e3ac-46ce-8a7d-4e07aa637537)

- Now I'll assign the ticket to Jane, I'll click `Unassigned`, select `Jane Doe`, then click `Assign`.

  ![2025-01-07 23_38_24-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/91355feb-294e-40cb-b097-b7361436b0a5)

- I'll post a reply for documentation.

  ![2025-01-07 23_41_12-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/f933c242-3c40-4b4c-829d-510cd13df626)

- For the sake of the lab, we will assume the system restart fixed the issue, so I'll post another reply, and close out the ticket.

  ![2025-01-07 23_43_52-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/b93fb597-9663-405a-b4bf-54e3b9b247d0)
  ![2025-01-07 23_49_40-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/a5d9880a-1068-4d87-8d4e-871dc288ba55)

</details>

<details>
  <summary>🛠️ Working a Personal Computer Issue Ticket</summary>

- I'll log in as Agent Jane, and work on the ticket about the CFO's laptop.

  ![2025-01-07 23_58_22-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/d0771b5a-c3ec-4963-9e4a-56dad030bdb2)

- I'll change the priority to `Emergency` and click `Update`.

  ![2025-01-08 00_00_25-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/26ed05ea-9198-4327-b8a2-da105b94ac30)

- Because this is not necessarily Business-Critical, I'll set the SLA to `Sev-B`.

  ![2025-01-08 00_03_44-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/f2af6526-9d23-4337-b324-241fb3d254bd)

- I'll assign the ticket to myself, click `Unassigned`, then select `Jane Doe`, then click `Assign`.

  ![2025-01-08 00_04_59-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/f2165518-8783-4d44-a1b0-5cc9f4f82f25)

- I'll post a reply that the laptop charger was broken.

  ![2025-01-08 00_09_29-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/ba173f78-88df-49ce-9350-6d0bed01bf85)

- Now I'll close the ticket and mark it as `Resolved`.

  ![2025-01-08 00_12_17-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/db053eae-00de-4781-8226-7e55c3d4e189)

</details>

<Details>
  <Summary>🛠️ Browsing Resolved Tickets</Summary>

- To review resolved tickets, I’ll log in as Adminuser, navigate to Tickets, and select Closed.

  ![2025-01-08 01_35_28-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/a0a85f92-c9c6-4231-a237-c416d9edc129)

- In the closed section, You can see all the resolved tickets that were closed by agents.

  ![2025-01-08 01_36_08-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/45ab8933-fd2e-45e1-b5b3-993eab8162a2)

- You can review the ticket thread to see the complete history, including the original post, all updates, changes, agent responses, and notes.

  ![2025-01-08 01_40_10-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/c7d565c0-1d9c-4ea9-8886-82542d6159ae)

  ![2025-01-08 01_40_28-48 211 167 121 - Remote Desktop Connection](https://github.com/user-attachments/assets/3c0f422c-c406-42c1-afbf-e551ce433576)

  
</Details>

---

<h2>💡 Key Takeaways</h2>

- The importance of setting the correct priority and SLA for each ticket.  
- Effective communication with users to ensure issues are addressed promptly.  
- Following a structured ticket lifecycle to maintain efficiency and resolution quality.

---

<p align="center">💻 Happy Ticketing! 💻</p>
