
How to edit this: test-2025
* Option-1 (tested and worked ok): PyCharm supports editing of these .md files. Then you need to push to the main branch or make a pull request.
* Option-2 (tested ok): Edit and commit it directly on github. Then any local repo copies will need to be "updated

# MyClean – Smart Cleaning Service Booking and Management Platform with Cloud Integration


## Project Overview
MyClean is a booking management application designed to help individual cleaners and cleaning companies manage their appointments, payments, and client communication efficiently. It also provides customers with a user-friendly platform to easily book, track, and review cleaning services.

## Team

It is recommended to complete this assignment in a group of 2-4 students.
1. Min Khant
2. Khun Pyae Heinn
3. Naing Phone Pyae
4. Nang Kaung Shan Kham


# Project planning BEFORE iteration-1, (see chapters 1-3)
Checklist/TODOs: 
* Update the following during each week prac session
* github entry timestamp is BEFORE the iteration-1
* User stories are correct: see p39
* Must have more user stories than fits into iterations 1 and 2. To practice the priority.
* [user story title](./user_stories/user_story_01_title.md), priority XX, YY days 
* ...

Total: YY days

## Week 1  
### Project Goals  
The goal of the **MyClean** project is to design and implement a cloud-powered platform that enables customers to easily book cleaning services and allows service providers to efficiently manage appointments, payments, and customer relationships. The platform will be accessible via both web and mobile devices, delivering robust and intuitive functionality tailored for both user groups.

---

### Key Features

1. **Real-Time Booking and Calendar Integration**  
   End-users can browse available service providers, view open time slots, and schedule cleaning appointments. Integration with calendar APIs (e.g., Google Calendar, Apple Calendar) will synchronize schedules for both customers and providers.

2. **Payment Gateway Integration**  
   The app will support secure payments through popular methods such as credit cards, e-wallets, and online banking. Payment processing will initially use mock interfaces during development, with plans to integrate real payment gateways (e.g., Stripe, PayPal) for production.

3. **Cloud-Based Data Storage and User Management**  
   User profiles, booking history, service preferences, and payment records will be securely stored using cloud services like Amazon S3 and DynamoDB. AWS Cognito will manage secure user authentication and role-based access control.

4. **Service Provider Dashboard**  
   Cleaners and cleaning companies will access a management dashboard featuring:  
   - Booking history  
   - Earnings reports  
   - Client reviews  
   - Profile customization (services offered, pricing, availability)

5. **End-User Portal**  
   Clients will be able to:  
   - Book one-time or recurring cleaning services  
   - Rate and review service providers  
   - Receive real-time appointment updates and reminders  
   - View past bookings and payment history

6. **In-App Messaging and Notifications**  
   Built-in messaging will facilitate communication between clients and providers regarding appointment details, custom requests, or rescheduling. Notifications via email or push alerts will inform users of confirmations, changes, and promotions.

7. **Unique Selling Points (USP)**  
   - **Smart Matching System:** AI-based algorithms will match users with providers based on location, availability, service type, and ratings.  
   - **Eco-Friendly Tagging:** Providers can label themselves as eco-friendly to attract environmentally conscious customers.  
   - **Subscription Plans:** Users can subscribe to regular cleaning services (e.g., weekly, monthly) with discounted rates.

8. **Analytics and Reporting**  
   Service providers will have access to analytical tools that display trends in client behavior, peak booking times, and earnings over time, aiding in business planning and optimization.

## Initial Backlog Ideas

| Priority | User Story                                                                                     |
|----------|------------------------------------------------------------------------------------------------|
| High     | As a cleaning service provider, I want to allow the clients and employees to register and log in securely, so they can access my personalized dashboard.  |
| High     | As a cleaning service provider, I want to featue available cleaning services to the customers, so that they can browse them    |
| High     | As a cleaning service provider, I want to manage my booking calendar, so that our employees can keep track of appointments.       |
| High     | As a cleaning service provider, I want to support payments through the app, so that the customers don’t have to pay in person.      |
| Medium   | As a cleaning service provider, I want to receive notifications about upcoming appointments, so I don’t miss them.  |
| Medium   | As a cleaning service provider, I want to track the status of my cleaning appointments and show them in real-time.            |
| Low      | As a cleaning service provider, I want to see monthly analytics of my bookings and earnings.                     |
| Low      | As a cleaning service provider, I want to receive ratings and reviews for the cleaning service after completion.                |
| Low      | As a cleaning service provider, I want to manage my profile including services offered and pricing.     |

---

## Iteration 1 [3-4 weeks] (Start: DD/MM/2025 - End: DD/MM/2025)

Goals: Implement core user authentication, browsing, and booking management functionalities such as calender, real-time status tracking and payment system.

1. User registration and login (priority: High)  
2. Service browsing and selection for customers (priority: Medium)  
3. Booking calendar management for cleaners (priority: Medium)
4. Browse cleaning services (priority: Low)
5. Support billing and invoicing (priority: Low)

**Total estimated effort:** 23 days

---

## Iteration 2 [3-4 weeks] (Start: DD/MM/YYYY - End: DD/MM/YYYY)

Goals: Add payment processing, notifications, and review system.

1. Payment gateway integration and invoicing (priority: Medium)  
2. Appointment notifications and reminders (priority: Medium)  
3. Reviews and ratings for service providers (priority: Low)  

**Total estimated effort:** XX days

---

## Not enough time/developers

In case of limited resources, these features can be deprioritized:

1. Monthly booking and earnings analytics (priority: Low)  
2. Real-time appointment status tracking (priority: Medium)  
3. Service provider profile management (priority: Low)  

**Total estimated effort:** XX days

---

# Actual iterations
1. [Iteration-1](./iteration_1.md)
2. [Iteration-2](./iteration_2.md)


