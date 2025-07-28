# Yield-Mart
 Online Shopping platform for economic center
Yeild Mart is a web-based platform I developed as part of a university web technology assignment to bridge the communication gap between farmers and consumers. The platform empowers farmers by enabling them to directly showcase and sell their agricultural produce to retailers or customers without intermediaries.

With features like real-time messaging, secure payment gateways, and product listing modules, Yeild Mart enhances transparency, ensures fair pricing, and promotes sustainable agriculture. I implemented role-based login systems for Admin, Manager, Delivery Employee, Farmer, and Customer accounts to handle different operations efficiently.

This project helped me gain valuable experience in:
✅ Web development using PHP, HTML, CSS, JavaScript
✅ Designing database schemas using MySQL
✅ Implementing role-based authentication and secure transactions
✅ Understanding real-world challenges in agriculture and how tech can solve them
✅ Building user-friendly interfaces and communication flows

🛒 Yeild Mart – Project Workflow & Account Roles
Yeild Mart is a multi-role web application designed to bridge the gap between farmers and consumers by streamlining the agricultural supply chain. The platform involves 5 main user roles with distinct functionalities:

👥 1. Admin Account
Manages all platform users (Farmers, Managers, Customers, Delivery Employees).
Can approve/reject accounts, update platform content, and monitor all transactions.
Has access to order status updates across all roles.

👨‍💼 2. Manager Account
Responsible for requesting fruits and vegetables from the platform.
Adds required products with desired quantities (e.g., 50kg mangoes).
Reviews farmers’ offers and:
Accepts the offer if price and quantity match needs.
Rejects the offer if the price is too high or stock is insufficient.
Can view customer orders and order statuses.

👨‍🌾 3. Farmer Account
Can view requests made by managers for specific fruits or vegetables.
Updates their available stock and sets their own price per quantity.
Awaits approval from the manager. If accepted, their produce is sold.
Can track transaction history and price negotiation outcomes.

🧑‍💻 4. Customer Account
Browses available fruits and vegetables listed by approved manager purchases.
Places an order with two payment options:
Cash on Delivery (COD)
Online Payment (Card)
Gets order status updates (pending, confirmed, dispatched, delivered).

🚚 5. Delivery Employee Account
Gets notified automatically once an order is confirmed by a customer.
Picks up the items and delivers to the customer’s address.
Issues invoice/bill receipt upon delivery.
Updates the order status to "Completed", which is reflected in:
Admin Dashboard
Manager Dashboard
Customer Order History

🔁 Order Workflow Summary:
Manager posts product needs →
Farmers respond with offers →
Manager accepts/rejects offers →
Accepted products become visible to Customers →
Customers place orders (COD/Card) →
Delivery person is notified →
Delivery is made with receipt →
Order marked "Completed" across all dashboards.

💡 Key Features:
Role-based login system for Admin, Manager, Farmer, Customer, Delivery.
Negotiation system between farmers and managers.
Secure payment integration (COD & Card).
Real-time notifications for delivery tasks.
Transparent order tracking for all users.

📌 Technologies Used:
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL
Security: HTTPS, encrypted user data
