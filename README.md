DCIT202 MOBILE APPLICATION DEVELOPMENT Assignment 6
Author: Gyabaah Theophilus
Student ID: 11038981
Project Overview
This project is part of the DCIT202 Mobile Application Development course. The objective is to recreate a design as seen in the UI mockup and implement functionality for a product listing and cart management system.

Project Structure
HomeScreen: Displays a list of available products.
CartScreen: Displays selected items in the cart.
Add to Cart Button: Allows users to add products to their cart.
Remove from Cart Button: Allows users to remove products from their cart.

Functionality
View Products: Users can view a list of available products.
Add to Cart: Users can add products to their cart.
Remove from Cart: Users can remove products from their cart.
View Cart: Users can view the items in their cart.
Data Storage
Data is stored locally on the device using AsyncStorage. This ensures that the cart's contents persist even if the app is closed or the device is restarted.

Design Choices
User Interface: The UI design is kept clean and simple, following the provided mockup closely to ensure a consistent user experience.
Local Storage: Chose AsyncStorage for its simplicity and ease of use for storing key-value pairs on the device.
State Management: Used React's useState and useEffect hooks to manage the state of the product list and cart.