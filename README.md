# Furniture-store

## Create Purchasing Information and Receipts for Lovely Loveseats

We’ve decided to pursue the dream of small-business ownership and open up a furniture store called Lovely Loveseats for Neat Suites on Fleet Street. With our newfound knowledge of Python programming, we’re going to build a system to help speed up the process of creating receipts for your customers.

In this project, we will be storing the names and prices of a furniture store’s catalog in variables. You will then process the total price and item list of customers, printing them to the output terminal.

<hr>

## Adding in The Catalog

###### Tasks

1. Add in your first item, the Lovely Loveseat that is the store’s namesake.<br>
Create a variable called `lovely_loveseat_description` and assign to it the following string:
> Lovely Loveseat: Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white.

2. Create a price for the loveseat.<br>
Create a variable `lovely_loveseat_price` and set it equal to `254.00`.

3. Extend our inventory with another characteristic piece of furniture!<br>
Create a variable called `stylish_settee_description` and assign to it the following string:
> Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black.

4. Set the price for our Stylish Settee.<br>
Create a variable `stylish_settee_price` and assign it the value of `180.50`.

5. Fantastic, we just need one more item before we’re ready for business.<br>
Create a new variable called `luxurious_lamp_description` and assign it the following:
> Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade.

6. Set the price for this item.<br>
Create a variable called `luxurious_lamp_price` and set it equal to `52.15`.

7. In order to be a business, we should also be calculating sales tax.<br>
Let’s store that in a variable as well.<br>
Define the variable `sales_tax` and set it equal to `.088`. That’s 8.8%.

## Our First Customer

8. Our first customer is making their purchase!<br>
Let’s keep a running tally of their expenses by defining a variable called `customer_one_total`.
Since they haven’t purchased anything yet, let’s set that variable equal to `0` for now.

9. We should also keep a list of the descriptions of things they’re purchasing.<br>
Create a variable called `customer_one_itemization` and set that equal to the empty string `""`.<br>
We’ll tack on the descriptions to this as they make their purchases.

10. Our customer has decided they are going to purchase our Lovely Loveseat!<br>
Add the price to `customer_one_total`.

11. Let’s start keeping track of the items our customer purchased.<br>
Add the description of the Lovely Loveseat to `customer_one_itemization`.

12. Our customer has also decided to purchase the Luxurious Lamp!<br>
Let’s add the price to the customer’s total.

13. Let’s keep the itemization up-to-date and add the description of the Luxurious Lamp to our itemization.