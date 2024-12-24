# IIUM SMASHERS

## Group Members

* Auni haziqah (2116050)
* Nur Raihan Syazwani binti Suhaimi (2213262)
* Muhammad Haqim Bin Hazhar (2210921)
* Nursyazira binti Mohd Naim (2214076)
* Nuralya Medina (2211788)

## Introduction

Effective management systems for sports facilities are becoming more and more in demand as badminton gains popularity as a recreational and competitive sport. This proposal describes the creation of a user-centric web platform specifically designed for badminton sports facility management in order to address this need. This platform's main objective is to completely transform how administrators and users manage court reservations, memberships, payments, and communication.The Model-View-Controller (MVC) architectural pattern will be used in the suggested system to guarantee a scalable and maintainable framework. The platform seeks to expedite crucial processes including court scheduling, membership enrolment, friendly sessions, and money processing by combining cutting-edge web technologies with user-friendly design concepts. This initiative seeks to address the inefficiencies of manual systems, such as time-consuming bookings, difficulty in tracking payments, and miscommunication between users and administrator.

An effective court management module, a user-friendly membership registration process, a centralised inquiry communication tool, and a reliable payment system are some of the platform's primary characteristics. Through friendly sessions that let users socialise and engage in leisure activities, the platform also encourages community involvement. The platform guarantees financial accountability and streamlines administrative duties by offering a transparent and safe payment tracking mechanism. In the end, this system will satisfy the requirements of administrators and users alike, promoting a smooth and effective experience in overseeing badminton sports facilities.

## Objectives

Designing and implementing a complete administrative web application that makes it easier to operate badminton sports facilities effectively is the main goal of this project. Enhancing operational workflows, improving user experiences, and creating a feeling of community among badminton enthusiasts are the goals of this platform. The project's precise goals are listed below:

-Boost the Effectiveness of Court Management
The system will give administrators a user-friendly interface to control court availability, reservations, and timetables. In order to ensure the best possible use of the facilities while minimizing manual labor, this provides tools for adding, modifying, and cancelling court reservations.
-Simplify the Management of Memberships
The platform streamlines the membership signup, renewal, and status update procedures by providing a centralized mechanism for managing member data. This will guarantee precise documentation and offer members a smooth registration process.
-Encourage Involvement in the Community
The system has a capability for setting up friendly sessions to promote social contact and leisure activities. A vibrant badminton community may be fostered by administrators who can establish, schedule, and monitor participant details.
-Facilitate Effective Communication
A robust "Contact Us" module will enable administrators to handle user inquiries efficiently. By providing tools for viewing, responding to, and managing communications, the platform aims to enhance user satisfaction and streamline issue resolution.
-Ensure Secure and Transparent Payment Management
The platform will incorporate a reliable payment tracking system to manage transactions related to court bookings and memberships. This includes real-time payment status updates, the ability to investigate and resolve payment issues, and generating detailed financial reports for administrative use.

By achieving these objectives, the proposed system will significantly improve the overall management and operational efficiency of badminton sports facilities. It will also provide a seamless experience for users, from booking courts to making secure payments, while fostering a sense of community and encouraging participation in recreational activities.

## Features and Functionalities

**Friendly session**

create : allow admin to create a friendly session by entering the details such as, session ID, Court number, category, date, time, and players name.

read : allow admin to read the friendly list database.

update : allow admin to update if there is any changes needed to update.

delete : allow admin to delete the friendly session from list.

**Member registration**

create: allow admin to insert new member in the databases along with member's informations.

read: allow admin to view list of members, members' informations and their membership status.

update: allow admin to edit members' informations.

delete: allow admin to delete members from list.

**Court Booking**

Admin View :

create (Add New Booking): Allow the admin to manually book a court for a member.

read (View All Bookings): View and filter all court bookings.

update (Edit Booking Details): Allow the admin to modify an existing booking.

delete (Cancel a Booking): Cancel an existing booking.


**Payment Method**

   View Payment Records (Read): The system displays a list of payment transactions, including:
    No: A sequential number for each transaction.
    User ID: A unique identifier for the user who made the payment.
    Payment ID: A unique identifier for the specific payment transaction (e.g., a transaction number).
    Amount: The amount paid (e.g., RM12, RM18).
    Date: The date the payment was made.
    Payment Method: The method used for payment (e.g., FPX, Credit Card, Touch 'n Go).
    Status: The current status of the payment (e.g., COMPLETE, PENDING).

Track Payment Status (Read): The admin can view the status of each payment, allowing them to monitor successful and pending transactions.

Generate Reports/Print (Output): The system provides a "PRINT" function, suggesting the ability to generate reports or print payment records for record-keeping and reconciliation.

Handle Pending Payments: a robust payment management system also includes the ability for the admin to:
    Manually update the status of pending payments: If a payment is confirmed through other means, the admin should be able to manually change the status to "COMPLETE."
    Investigate failed or incomplete payments: The system provides tools to help the admin identify and resolve payment issues.

**Contact Us**

Create: Allows the admin to respond to user inquiries by clicking the "Reply" button. Admin is redirected to a page where they can compose a reply, which will be sent to the user's email.

Read: Enables the admin to view a list of all user inquiries. This list includes details such as the user's name, matric number, email, message content, and the date/time of submission.

Update: Admin can manage and update previous replies or resend a message to users if necessary.

Delete: Admin can delete inquiries from the list once they are resolved or no longer relevant.


## ERD 
![webapp drawio (4)](https://github.com/user-attachments/assets/a602783d-ee5e-4251-b034-61ebd7da824a)

## Sequence Diagram
![IIUM Smashers Sequence Diagram](https://github.com/user-attachments/assets/aad11a1b-1cd8-414c-9df1-26afbbf43847)

## Mockups

**Court Booking**

![Screenshot 2024-12-24 214601](https://github.com/user-attachments/assets/acba08e1-0023-4dcc-84c1-80a06cd2f84d)
![Court Booking (2)](https://github.com/user-attachments/assets/79887576-2ce3-43b3-a188-4dbc99cc0311)
![Court Booking (3)](https://github.com/user-attachments/assets/20ee2981-755d-49b1-87ae-dd46ba3a8f68)


**Membership**
![Membership 1](https://github.com/user-attachments/assets/c1e48196-8243-4835-8faf-8c7a2b02dc26)
![Membership 2](https://github.com/user-attachments/assets/124e6f2f-0bd0-4481-9f64-b175045539c3)
![Membership 3](https://github.com/user-attachments/assets/f943b1bd-4c19-4a21-82db-b19d4f4c5c73)
![Membership 4](https://github.com/user-attachments/assets/4548ca28-ef49-4f33-8ac3-6301babf1229)
![Membership 5](https://github.com/user-attachments/assets/3dee0dae-3db8-4e72-88ba-7102f8b13dc7)

**Friendly Session**

![friendly1](https://github.com/user-attachments/assets/216130df-8500-4241-a25d-066db3cb3fd9)

![friendly2](https://github.com/user-attachments/assets/21bb5b6d-0a79-4b4c-a5bc-d8aa2565578c)

![friendly3](https://github.com/user-attachments/assets/7c1abf87-f44f-48d6-908c-7d185deedd40)


**Contact Us**

![Contact Us 1](https://github.com/user-attachments/assets/eacd2c0e-c915-416b-9c9c-775c2192242f)

![Contact Us 2](https://github.com/user-attachments/assets/559570b3-4bb7-44c8-8a5d-1e2316966ee3)

![Contact Us 3](https://github.com/user-attachments/assets/2f54bb6a-1b5e-44bf-b321-d00ac9f70279)

![Contact Us 4](https://github.com/user-attachments/assets/cbe551d4-4006-480f-ad62-49a97cb01b81)

**Payment**
<img width="712" alt="PAYMENT 1" src="https://github.com/user-attachments/assets/23d342ba-e368-4e8c-bb3a-8720a05ad895" />
<img width="598" alt="PAYMENT2" src="https://github.com/user-attachments/assets/afb983c2-36c0-4796-a562-f73c5e6020a3" />
<img width="600" alt="PAYMENT3" src="https://github.com/user-attachments/assets/a75dec50-0929-48f2-b7bf-f75aa7adc58a" />



## References

