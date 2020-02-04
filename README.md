# Eatin
## Front-end of a smart room service(food-ordering) website group project.

## Vision
The main objective of our project is to develop a prototype of an online food ordering system for a hotel. This is a self-ordering system and can be accessed via the tablet provided to each hotel room. This application can be used by the guests to place orders and have them delivered to any venue/room of their preference inside the hotel. Once the operator (guest) has placed an order, it is processed by the system into a simple readable format and forwarded to a display in the kitchen. The display is accessible to everyone in the kitchen and therefore the staff can start the preparation quickly. The system is updated by a staff member to let the customer know the estimated time of delivery depending on what they ordered. After the order is prepared, an employee will deliver the food to the mentioned location and the payment is added to the guest’s hotel bill. The purpose of the system is to reduce manpower and inconveniences caused by manual food ordering systems, resulting in an efficient and secure smart-system for both the hotel and its guests. 

## Project Description
We built this prototype based on the low-fidelity prototype and the prototype evaluation from the
milestone 2. We kept the simple and intuitive layout from the low fidelity prototype but eliminated some
elements that confused the users we got feedback from. According to the users’ feedback from the
low-fidelity prototype, we added item modification function to the checkout page so that the users can
modify their order during checkout.
We used Bootstrap grid system to do the layout of the website and jquery modal to implement the
pop-up windows features. For multiple languages support, we use Google Translate scripts. The website
is formatted by CSS document and inline CSS.



## 1) Major features
## Multiple language interface
The prototype supports multiple language interface allowing users from different countries to use
the system. The display language can be changed in different ways. One way is by clicking one of the flag
icons with the respective language on the welcome page. Another way is to click the global language
icon( ) on the top right corner, and then choose the desired language. And the last way to change the
display language is by clicking on the option “More”, then clicking on the “Select Your Language”, and
then choosing the preferred language.

![Add_posts](https://raw.githubusercontent.com/juliek1217/eatin/master/Eatin/posts1.PNG)


## Menu with detailed information
This feature provides more detailed information about the food item to the users. When a user
clicks on a food item, a smaller pop-up window appears showing a larger picture of the food, the
ingredients that appear in the dish, and the nutrition information about the item. The nutrition information
includes the number of calories, fats, carbohydrates, sodium and proteins.

## Placing order
This prototype allows users to place the order. If the users visit the checkout page and press the
“Order now”, it will allow them to place the order. When the order is placed, the screen will change to the
one with the information about the placed order and a message which includes the estimated delivery
time, location where the food will be delivered and the option to go back to the main menu.

## Order history
The “Order History” option lists out all the orders (previous and current) of the user. Important
information about the order such as the order number, date the order was placed, total cost and the status
are shown for each order. The status will say “Order Delivered” if the user has already received the dishes
to their room. On the other hand, if it says “Order Confirmed”, the user has an alternative to cancel or
modify the order according to their preference. The order number is illustrated as a link to convey the user
that they can click on it for additional functions.



## 2) Showcase

## Welcome Page
Welcome page with multiple language options and featured menu.
This gives the user an overview of our website.
Sidebars
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/welcome%20page.png)
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/multilanguage.png)

## Sidebars
Fixed-position categorized menu (left sidebar) and shopping cart (right sidebar).
The users always have access to different category of menu and shopping cart. The fixed-position
shopping cart enables users to track their items in the shopping cart.
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/shoppingcart.png)


## Food Item Description
Detailed food menu with picture, ingredients, and nutrition information.
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/menudetailpopup.png)

## Checkout
Check out page allows users to review and modify their order. It provides an estimated delivery time to
the users. Pre-order function is also available inside this page.
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/checkout.png)

## Order History
Users can review their previous orders and modify or cancel the current orders.
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/orderhistory.png)
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/order.png)


## Others
Users can review their previous orders and modify or cancel the current orders.
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/languageoptionpopup.png)
![Profile](https://github.com/juliek1217/eatin/blob/master/Eatin_pics/moreservice.png)
