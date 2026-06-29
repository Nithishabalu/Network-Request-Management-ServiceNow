# Network Request Management System using ServiceNow

## Project Overview

The Network Request Management System is a ServiceNow-based application developed to automate the process of handling network-related service requests within an organization. The system allows employees to submit network requests through the Service Catalog, routes requests for approval, creates tasks for the Network Team, updates request status automatically, and sends email notifications to users throughout the request lifecycle.

This project demonstrates the use of ServiceNow Administration, Service Catalog, Flow Designer, Catalog Client Scripts, User Management, Role Management, and Workflow Automation.

---

## Objectives

- Automate network request submission.
- Reduce manual approval processes.
- Automatically assign tasks to the Network Team.
- Track request status from submission to completion.
- Improve communication through email notifications.
- Provide secure role-based access.

---

## Features

- User Registration and Role Management
- Group Management (Network Team, Approvers, Requesters)
- Service Catalog Item for Network Requests
- Catalog Variables
- Dynamic Form using Catalog Client Script
- Automated Approval Workflow
- Automatic Catalog Task Creation
- Request Status Tracking
- Email Notifications
- Reports and Dashboards

---

## Technologies Used

- ServiceNow Developer Instance
- Flow Designer
- Service Catalog
- Catalog Client Script (JavaScript)
- Email Notifications
- Custom Tables

---

## Modules

### User Management
Created users with different responsibilities such as Employee, Manager, Network Engineer, and Administrator.

### Role Management
Configured roles to provide secure access to different users.

### Group Management
Created groups including:
- Network Team
- Approvers
- Requesters

### Service Catalog
Developed a catalog item called **Network Request** where users can submit requests.

### Catalog Variables
Added variables including:
- Request Type
- Access Level
- Device Name
- Business Justification
- Attachment

### Catalog Client Script
Implemented client-side scripting to dynamically display fields based on the selected request type.

### Flow Designer
Created an automated workflow that:
- Sends requests for approval.
- Creates Catalog Tasks.
- Assigns tasks to the Network Team.
- Updates request status.
- Sends email notifications.

---

## Workflow

1. Employee submits a Network Request.
2. Request is sent for approval.
3. Approver reviews and approves the request.
4. Flow automatically creates a Catalog Task.
5. Task is assigned to the Network Team.
6. Network Team processes the request.
7. Request status is updated.
8. Email notification is sent to the requester.
9. Request is completed successfully.

---

## Advantages

- Reduces manual effort.
- Faster approval process.
- Automatic task assignment.
- Better request tracking.
- Secure role-based access.
- Improved communication through notifications.
- Easy monitoring using reports and dashboards.

---

## Future Scope

- Multi-level approvals.
- SLA implementation.
- Active Directory integration.
- Mobile application support.
- AI-based request recommendations.
- Advanced dashboards and analytics.

---

## Conclusion

The Network Request Management System successfully automates the complete lifecycle of network service requests using ServiceNow. The project improves operational efficiency, reduces manual work, enhances transparency, and ensures proper tracking of requests through automated workflows and notifications.

---

## Screenshots 

- Application
- Custom Table
- Service Catalog Item
- Variables
- Catalog Client Script
- Flow Designer
- Approval Process
- Catalog Task
- Email Notification
- Dashboard

---

## Author

**Name:** NITHISHA B

**Platform:** ServiceNow Developer Instance

**Project:** Network Request Management System

---

## Thank You

Thank you for reviewing my ServiceNow project.
