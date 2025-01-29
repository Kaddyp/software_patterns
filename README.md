# Software Architectural Patterns

Here are some essential software architectural patterns that are crucial for every developer to understand. 
But don't worry, I'll keep it simple and easy to understand for everyone.

## 𝐄𝐯𝐞𝐧𝐭 𝐃𝐫𝐢𝐯𝐞𝐧 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞 (𝐄𝐃𝐀): 
It's all about things happening in response to events, like when one thing sets off another, just like how a chain reaction work.
=> Use Cases:
Online Marketplace: Notifying users about product discounts or new arrivals.
IoT Devices: Reacting to sensor data to automate processes or trigger alert.
=> Components: 
Events (such as user interactions), Event Handlers, Event Bus (distributed events).

## 𝐋𝐚𝐲𝐞𝐫𝐞𝐝 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞:
It divides the system into logical layers, each responsible for a specific aspect of functionality. Like organizing a house where you have different floors for different activities.
=> Use Cases:
Banking System: Separating user interface, business logic, & database operations.
Social Media Platform: Organizing features like profiles, feeds, & notifications.
=> Components: 
Presentation Layer (UI), Business Logic Layer (processing logic), Data Access Layer (database interaction).

## 𝐌𝐨𝐧𝐨𝐥𝐢𝐭𝐡𝐢𝐜 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞:
All components of the application are tightly coupled into a single codebase and deployed as a single unit.
=> Use Cases:
Content Management System: Combining content creation, publishing, and management functionalities.
Enterprise Resource Planning System: Incorporating modules for HR, finance, and etc.
=>Components : Single codebase.

## 𝐌𝐢𝐜𝐫𝐨𝐬𝐞𝐫𝐯𝐢𝐜𝐞𝐬 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞:
Breaks the system into smaller, independent services, each focused on a specific business capability.
=> Use Cases:
E-Commerce: Handling product catalog, order processing, and user authentication as separate services.
Travel Booking System: Managing flight bookings, hotel reservations, and payment processing independently.
=> Components: 
Independent services communicating via APIs, each with its own database.

## 𝐌𝐨𝐝𝐞𝐥 𝐕𝐢𝐞𝐰 𝐂𝐨𝐧𝐭𝐫𝐨𝐥𝐥𝐞𝐫 (𝐌𝐕𝐂):
MVC separates the application into three interconnected components: Model, View, & Controller. 
=> Use Cases: 
Web Development: Structuring web applications with separate layers for data, presentation, & user interaction.
=> Components: 
Model (data structure), View (user interface), Controller (logic to handle user input).

## 𝐌𝐚𝐬𝐭𝐞𝐫-𝐒𝐥𝐚𝐯𝐞 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞:
It involves one central node (master) controlling one or more subordinate nodes (slaves). 
=> Use Cases: 
Database Replication: Replicating data from master database to multiple slave databases for read operations.
=> Components: 
Master node (handles write operations), Slave nodes (replicate data for reads).
