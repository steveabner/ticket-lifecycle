<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" width="200"/>
</p>

<h1 align="center">🎫 osTicket - Ticket Lifecycle: Intake Through Resolution 🎫</h1>
<p align="center">
  This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system, osTicket.
</p>

---

<!--<h2 align="center">📽️ Video Demonstration 📽️</h2>

<p align="center">
  ▶️ <a href="https://www.youtube.com">Watch on YouTube: How to create, work, and resolve tickets within osTicket</a> ◀️
</p>-->

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
  <summary><strong>📝 Creating Tickets</strong></summary>
  <ol>
    <li>
      Navigate to the Support Center URL: <a href="http://localhost/osTicket" target="_blank">http://localhost/osTicket</a>, and click <code>Open a New Ticket</code>.  
      <img src="https://github.com/user-attachments/assets/772ba996-bc85-46b9-b448-4c561cc27947" alt="Open New Ticket Screenshot" width="80%">
    </li>
    <li>
      Create three tickets by filling in the user's information, describing the issue, and selecting the appropriate help topic.  
      <img src="https://github.com/user-attachments/assets/37993a64-3d9e-4df0-8dca-6e7e863de04a" alt="Ticket Creation" width="80%">
    </li>
    <li>Click <code>Create Ticket</code> to finalize each submission.</li>
  </ol>
</details>

<details>
  <summary><strong>🛠️ Working a Business Critical Ticket</strong></summary>
  <ol>
    <li>
      Log in as Help Desk agent <strong>Jane</strong>.  
      <img src="https://github.com/user-attachments/assets/e91108a1-ab6c-4682-930e-1db51f8b27c7" alt="Agent Jane Login" width="80%">
    </li>
    <li>
      View all tickets and begin with the oldest. Review its details, such as <code>Priority</code>, <code>Department</code>, <code>SLA</code>, and <code>Assigned To</code>.  
      <img src="https://github.com/user-attachments/assets/0556fd27-0301-4d25-b01e-1f1d0e4601ac" alt="Ticket Details" width="80%">
    </li>
    <li>
      Set the priority to <code>Emergency</code>, update the SLA, and assign it to the appropriate team.  
      <img src="https://github.com/user-attachments/assets/35abe897-6751-49ff-92a5-cb7c538fd068" alt="Update SLA" width="80%">
    </li>
    <li>
      Work on the ticket as <strong>John</strong>, update the status, communicate with the user, and close the ticket.  
      <img src="https://github.com/user-attachments/assets/93b72fc2-b99b-4b70-8694-14f54105839e" alt="Communicate with User" width="80%">
    </li>
  </ol>
</details>

<details>
  <summary><strong>🛠️ Working a General Inquiry Ticket</strong></summary>
  <ol>
    <li>
      Log in as Help Desk agent <strong>Jane</strong>, review the ticket, and determine the SLA based on urgency.  
      <img src="https://github.com/user-attachments/assets/d5d723de-b9c4-4eec-8cd7-6e785aa05707" alt="General Inquiry Ticket" width="80%">
    </li>
    <li>Assign the ticket to yourself, post replies, and resolve the issue.</li>
  </ol>
</details>

<details>
  <summary><strong>🛠️ Working a Personal Computer Issue Ticket</strong></summary>
  <ol>
    <li>
      Prioritize the ticket based on urgency and set the SLA.  
      <img src="https://github.com/user-attachments/assets/f2af6526-9d23-4337-b324-241fb3d254bd" alt="Update SLA" width="80%">
    </li>
    <li>Assign the ticket to yourself, post updates, and close the ticket after resolution.</li>
  </ol>
</details>

---

<h2>💡 Key Takeaways</h2>

- The importance of setting the correct priority and SLA for each ticket.  
- Effective communication with users to ensure issues are addressed promptly.  
- Following a structured ticket lifecycle to maintain efficiency and resolution quality.

---

<p align="center">💻 Happy Ticketing! 💻</p>
