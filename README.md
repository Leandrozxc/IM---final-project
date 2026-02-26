## UNIVERSITY SERVICE HELPDESK


## 🎓 Student Services Helpdesk Web Application

The **Student Services Helpdesk** is a centralized, web-based ticketing system designed to streamline how universities manage and resolve student concerns. The application addresses the common problem of fragmented communication channels—such as walk-ins, emails, and chat messages—that often lead to lost requests, unclear responsibilities, and delayed resolutions.

### 🚩 Problem Overview

In many universities, students struggle to identify the correct office (IT, Registrar, Facilities, etc.) to handle their concerns. Once a report is submitted, students are forced to repeatedly follow up with no visibility into its status. On the administrative side, staff and department heads are overwhelmed by requests coming from multiple sources, making it difficult to track progress, prioritize urgent issues, and generate meaningful reports.

### 💡 Proposed Solution

This web application provides a **single, centralized platform** where all student service requests are submitted, categorized, assigned, and tracked. By consolidating all concerns into one system, the Helpdesk improves transparency for students and operational efficiency for administrators through real-time status tracking and structured data management.

---

🧩 Core Features
👥 User Roles

**Students**
  Submit service requests (tickets), view real-time updates, and add follow-up messages.**Staff / Encoders**
  File tickets on behalf of students and work on assigned requests.
 **Admins / Department Heads**
  Categorize tickets, assign them to staff, manage ticket statuses, and generate performance and workload reports.

### 🔄 Ticket Lifecycle & Business Logic

* Every ticket is automatically assigned a **unique Ticket Number** and **Created Date** upon submission.
* Each ticket is linked to **one student requester** and **one department** (e.g., IT, Registrar, Facilities).
* Tickets require a valid **category**, **priority level**, and **detailed description** to ensure clarity and data integrity.
* The system enforces a controlled **status workflow**:
  **Open → Assigned → In Progress → On Hold → Resolved → Closed**
* Only **admins** can mark tickets as *Resolved* or *Closed* to ensure proper validation and accountability.
* A ticket may only be assigned to **one active staff member at a time**, with reassignment requiring a documented reason.
* **Urgent tickets** require a justification to prevent misuse of high-priority flags.
* All ticket updates are recorded in an **audit trail**, capturing who made changes, when they were made, and why.
* The system detects **potential duplicate submissions** within a 24-hour window and allows tickets to be linked or merged.
* An **administrative dashboard** displays open and overdue tickets by department and staff, enabling better prioritization and performance monitoring.

###📊 Impact & Value

By implementing the Student Services Helpdesk, universities gain:

* Improved transparency and communication for students
* Reduced administrative workload and lost requests
* Clear accountability through role-based access control
* Data-driven insights for service performance and resource allocation

This project demonstrates the practical application of **information management principles**, including data integrity, process standardization, access control, and organizational decision support, within a real-world university setting.

