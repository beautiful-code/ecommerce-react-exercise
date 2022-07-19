# Exercise 4

## Goal
Implement Add to Cart Functionality.


### Requirements
1. On click of addToCart item should be added to the cart. Store cart details in Recoil State.
![Addcart button](https://github.com/beautiful-code/ecommerce-react-exercise/blob/161c9bce0527d0eb03b8567ea94e05b6f45a8645/images/Screenshot%202022-07-19%20at%202.34.13%20PM.png)
2. Add and Remove items from cart ( - and + ). If the item is present in cart then instead of Add to Cart button show the following.
![Goal ](https://github.com/beautiful-code/ecommerce-react-exercise/blob/main/images/Screenshot%202022-07-19%20at%202.26.09%20PM.png)
In the above image, the number between plus and minus buttons is the current quantity in the cart.

3. On click of cart button, show the items in the card as follows:
![cart](https://github.com/beautiful-code/ecommerce-react-exercise/blob/870f0839cd7b0af9ca4548b9b150e65ad6b0c09d/images/Screenshot%202022-07-19%20at%202.25.13%20PM.png)
Price is calculated by price per item * quantity in the cart.
The above cart dropdown is shown only if cart button from header is clicked.



### Hints:
1. Use Recoil for managing React State
2. In the cart dropdown the quantity should be equal to the quantity added to the cart.


