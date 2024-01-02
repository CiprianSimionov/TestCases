
# Gotica-TestCase

Below are some samples created for my previous projects.

*Title*: Test login with incorrect credentials

*Description*: Check if the login works when a customer uses incorrect user/pass

*Steps to reproduce*:
1. Go to https://www.gotica.ro/logare.html
2. Add incorrect user and password
3. Press the "Login" button

*Expected Result*: User shouldn't be able to login and it gets an error message.

*Test Data*: User: cipriabbath@gmail.com & Pass: come1234

-----------------------------------------------------------------------

*Title*: Test login with correct credentials

*Description*: Check if the login works when a customer uses correct user/pass

*Steps to reproduce*:
1. Go to https://www.gotica.ro/logare.html
2. Add correct user and password
3. Press the "Login" button

*Expected Result*: User should be able to login.

*Test Data*: User: cipriabbath@gmail.com & Pass: comerace1234

-----------------------------------------------------------------------

*Title*: Test "Remember me" checkbox

*Description*: Verify if "Remember me" checkbox works when a customer checks it

*Steps to reproduce*:
1. Go to https://www.gotica.ro/logare.html
2. Check "remember me" checkbox before login with valid credentials

*Expected Result*: User should be able to login.

*Test Data*: User: cipriabbath@gmail.com & Pass: comerace1234

-----------------------------------------------------------------------

*Title*: Valid search

*Description*: search for an existing product

*Steps to reproduce*:
1. Access https://www.gotica.ro/
2. search for an existing product
3. Press "search" button

*Expected Result*: Searched product should be returned and listed

*Test Data*: product name: "cana jingle beer"

-----------------------------------------------------------------------

*Title*: Autocomplete search

*Description*: Verify if for entered keyword displayed appropriate options

*Steps to reproduce*:
1. Access https://www.gotica.ro/
2. Type first 4 letters from an existing product

*Expected Result*: A list of searched products should be displayed

*Test Data*: product name: "nano" from "hanorac"

-----------------------------------------------------------------------

*Title*: Search unavailable items

*Description*: Search for a product that is not available in the inventory

*Steps to reproduce*:
1. Access https://www.gotica.ro/
2. search for an inexisting product
3. Press "search" button

*Expected Result*: Search results should display “Item not found." message

*Test Data*: product name: "frigider"

-----------------------------------------------------------------------

*Title*: Set item quantity to 0

*Description*: Access main cart with added items

*Steps to reproduce*:
1. Access https://www.gotica.ro/
2. Select one item from shopping cart with quantity different than 0
3. Set item quantity to 0

*Expected Result*: The item should be removed from cart.
	             The cart total price should be updated.

-----------------------------------------------------------------------

![testCases1](https://github.com/CiprianSimionov/TestCases/assets/26772192/f4362960-353f-44d2-9b82-1a6b8b3c095b)



