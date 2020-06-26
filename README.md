# Real-time web application for making and managing restaurant orders

This is a web applications which primary functionality is managing restaurant orders in real-time. There are three user roles in the application - guest (unregistered customer), registered customer and restaurant waiter. Customers can make orders when they arrive at the restaurant and restaurant waiter receives and manages the orders customers make in real-time. Real-time communication between the customer and the waiter is accomplished using WebSocket protocol.

## Use case scenario

The application use case scenario is as following: the waiter signs in the application in the restaurant and a dashboard is displayed showing all the restaurant tables (which he earlier added in the application) along with table statuses (empty or occupied). On the same screen the new orders are dynamically shown in real-time as customers make them. Restaurant waiter can add his restaurant's tables in the application and each table has a unique sharing id based on which a unique link is created which, when clicked on, allows customers to create a new order specifically for that table. Due to practical reason, the application generates a QR code for each restaurant table which contains the mentioned link for created a new order. The QR code can then be printed on a paper and placed on the table so customers could scan the QR code using their mobile phones. After user sits at a table and scans the QR code which is placed on that table, the application opens in his web browser and allows him to create a new order for the table he is sitting at. After he choses items he wants to order, he clicks the order button and the order shows up in the waiter's dashboard. Waiter can then see which items the customer orderd and after he serves him the items, he marks the order as served. When the order is marked as served, the customer is notified and can either add new items to his order or he can request a receipt. If he adds new items to the order, the order is again shown to the waiter and he can mark it as served. If he chooses to get a receipt, the waiter gets notified about that and after he brings the receipt to the customer which he pays, he marks the order as paid. When the order is marked as paid, the order is finished and the table changes status from occupied to empty.

## Duration
- March 2020 - June 2020

## Technologies used
Front-end:
- HTML
- CSS
- JavaScript
- React
- Redux
- Bootstrap Framework
- AJAX
- Socket.io

Back-end:
- Node.js
- Express
- Socket.io

Database management:
- MySQL

## Features and user roles
Restaurant waiter
- can add and modify restaurant tables, menu categories and menu items
- can manage orders in real time as they are made
- can view all previous orders and order details

Guest:
- can make a new restaurant order

Registered customer:
- can make a new restaurant order
- can view all previous orders

## Real-time communication

## Screenshots

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/1.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/2.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/3.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/4.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/5.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/6.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/7.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/8.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/9.png" alt=""	width="100%" />

<img src="https://github.com/fifi98/RestaurantOrdersPublic/blob/master/screenshots/restaurant/10.png" alt=""	width="100%" />




