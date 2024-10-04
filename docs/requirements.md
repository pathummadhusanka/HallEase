# Functional Requirements

### 1. User Management

System should allow to register new users and also interact with already signed up users.
There should be a priority base access control

- **Admin** - *Administrators can manage all users, halls, and bookings.*  
- **Users** - *can view hall availability and book halls under certain conditions.*


### 2. Hall Booking System

- **View available halls** - The system shall allow users to view available halls for booking based on date, time, and capacity.

- **Book a hall** - Users can select an available hall and book it by specifying the event details by filling a form (date, time, purpose, number of attendees).

- **Modify or Cancel** 
    - if it is an admin, they can cancel a reservation by point out the reason

    - also a user can cancel or modify the booked reservations

### 3. Calender & Graphical representation

- **Calendar** 
    - The system shall display bookings and availability on a calendar view, showing daily, weekly, and monthly schedules for each hall.

    - The system shall allow users to filter the calendar by date and hall to see specific availability.

- **Graphical Interfaces**(optional)
    - Users can view the hall in graphical view. it should display the details of that hall

### 4. Notifications and Alerts

- **Confirmations**
    - The system shall send email or SMS notifications to users upon successful booking, modification, or cancellation of a hall.

- **Reminders** 
    - The system shall send reminder notifications 24 hours before the booked event.

- **Canceled Booking Alerts**
    - The system shall notify users if their booking is canceled by an administrator or if there are overdue payments (if applicable).


---
> Later developments

### 5. AI/ML Features

- Demand Prediction

- Smart Recommendations

- Automated Scheduling Optimization

- Reporting and Analytics

### 6. Key Management System

### 7. Wastage Management System