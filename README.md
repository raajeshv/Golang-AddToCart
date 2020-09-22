# Golang-AddToCart

# Golang-Project-backend


This project was developed by Rajesh Kannan.

Requirements:-

Candidate Take Home Test
Have you shopped online? Let’s imagine that you need to build the checkout
backend service that will support different promotions with the given inventory.
Build a checkout system with these items:
SKU Name Price Inventory Qty
120P90 Google Home $49.99 10
43N23P MacBook Pro $5,399.99 5
A304SD Alexa Speaker $109.50 10
234234 Raspberry Pi B $30.00 2
The system should have the following promotions:
Each sale of a MacBook Pro comes with a free Raspberry Pi B
Buy 3 Google Homes for the price of 2

Buying more than 3 Alexa Speakers will have a 10% discount on all Alexa
speakers
Example Scenarios:
Scanned Items: MacBook Pro, Raspberry Pi B
Total: $5,399.99
Scanned Items: Google Home, Google Home, Google Home
Total: $99.98
Scanned Items: Alexa Speaker, Alexa Speaker, Alexa Speaker
Total: $295.65


- How to run project
download source code or clone it in your computer then go to the root path of the project. then run 

go get -u ./...

for get all the dependency used in this project. then make a database in Postgres and add your database config into /config/config.go
and go to the root project directory and run 

go run main.go
