# IT-Ticketing-PowerApps
Low-code IT support ticketing system built with Power Apps and Power Automate, using Excel (OneDrive) for data storage and automated email notifications.

# IT Support Request Automation System (Power Apps + Power Automate)

## Overview

This project is a low-code IT support ticketing system built using Microsoft Power Apps and Power Automate. It allows users to submit support requests through a simple form interface, stores the data in a structured Excel table (OneDrive), and automatically sends email notifications when a new ticket is created.

The goal of this project is to demonstrate practical business process automation using the Microsoft Power Platform.

---

## Features

- Submit IT support requests through a user-friendly form
- Capture structured data including:
  - Requester Name
  - Department
  - Issue Title
  - Issue Description
  - Priority Level
- Store tickets in an Excel table hosted on OneDrive
- Automatically send email notifications upon submission using Power Automate
- Reset form after submission for continuous use

---

## Tech Stack

- **Microsoft Power Apps** – Frontend form interface
- **Microsoft Power Automate** – Workflow automation and email notifications
- **Excel (OneDrive)** – Data storage (table-based backend)

---

## System Workflow

1. User fills out the IT support request form in Power Apps
2. On submission:
   - Power Apps writes the ticket data to an Excel table
   - A Power Automate flow is triggered
3. Power Automate sends an email notification with ticket details
4. The form resets and is ready for the next submission

---

## Screenshots

### Application Interface
<img width="1394" height="780" alt="APPLICATION INTERFACE" src="https://github.com/user-attachments/assets/3e8c3c85-616c-4c79-88c3-f033754306ed" />

### Ticket Submitted Successfully
<img width="1676" height="872" alt="TICKED SUBMITTED SUCCESSFULLY" src="https://github.com/user-attachments/assets/3a7e1fe8-fccf-4f03-b25b-0896a375346f" />


### Excel Data Storage
<img width="1471" height="648" alt="EXCEL SHEET UPDATED" src="https://github.com/user-attachments/assets/d8a75a0f-82ce-46ff-889a-5c898dd11fd2" />


### Email Notification
<img width="1347" height="648" alt="EMAIL NOTIFICATION SUCCESS" src="https://github.com/user-attachments/assets/66d9bd00-6bb5-40f5-a00c-f51fb9a1fc93" />

---

## Key Learning Outcomes

- Built a functional low-code application using Power Apps
- Integrated Power Apps with external data sources (Excel in OneDrive)
- Developed a Power Automate workflow triggered from a Power Apps button
- Implemented real-time business process automation
- Gained insight into limitations of Excel as a backend data source

---

## Limitations

- Excel-based storage can become **file-locked** if the workbook is open, preventing writes from Power Apps
- Not ideal for multi-user or production environments
- Limited scalability compared to enterprise-grade data solutions

---

## Future Improvements

- Replace Excel with **SharePoint Lists** or **Dataverse** for better reliability and scalability
- Add a **ticket status tracking dashboard** within Power Apps
- Implement **priority-based escalation** (e.g., urgent email alerts for high-priority issues)
- Add user authentication and role-based access control
- Create reporting and analytics for ticket trends

---

## How to Run / Use

1. Open the Power Apps application
2. Fill in the required fields:
   - Name
   - Department
   - Issue Title
   - Description
   - Priority
3. Click **Submit**
4. Ticket will be:
   - Saved to Excel (OneDrive)
   - Sent via email notification

---

## Project Purpose

This project was developed as part of portfolio preparation to demonstrate practical skills in:

- Low-code development
- Workflow automation
- Business process design
- Microsoft Power Platform tools

---

## Author

**Keshan Williams**  
GitHub: https://github.com/SekhmetDivine
