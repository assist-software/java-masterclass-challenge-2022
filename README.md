# The Supermarket Receipt

#### Description:
The supermarket has a catalog with different types of products (rice, apples, milk, toothbrushes,...). Each product has a price, and the total price of the shopping cart is the total of all the prices of the items. You get a receipt that details the items you've bought, the total price and any discounts that were applied.

The supermarket runs special deals, e.g.
 - Buy two toothbrushes, get one free. Normal toothbrush price is €0.99
 - 20% discount on apples, normal price €1.99 per kilo.
 - 10% discount on rice, normal price €2.49 per bag
 - Five tubes of toothpaste for €7.49, normal price €1.79
 - Two boxes of cherry tomatoes for €0.99, normal price €0.69 per box.

These are just examples: the actual special deals change each week.

Create some test cases and aim to get good enough code coverage that you feel confident to do some refactoring.

### Your exercise:
***
#### The aim of the exercise is to refactor this code, and if you have time to add new feature.

The challenge is to restructure the code in such a way, that you can extend the application with 
new features. Ideally, each new feature should be possible by modifying 0 to a maximum of 1 
file of code that already existed.
And on top of all this: the code should remain testable and tested!

#### Challenge in summary
***
> Clone the repository

> Go through you code and identify something you think can be improved

> Identify code smells such as Long Method

> Use any libraries if necessary to want to make code more readable and easy-to-understand 

> Apply SOLID principles

> Apply relevant design patterns

>  Restructure the code, so that
  >> is still testable

#### Rules
***

* Use Java 11 or above
* Don't modify the assertions from unit tests

#### Bonus points for
***
* Use immutable types as much as possible
* Use functional programming approaches as much as possible
* Better naming for existing classes, variables, packages, etc.

When you're confident you can handle this code, and you have time, you can implement the new 
feature described below

##### New feature: HTML receipt
***
Currently, we print a traditional ticket receipt.
Now beeing a modern business we'd like to be able to print or send an HTML version of the same receipt.
All the data and number formatting should be the same. However, the layout should be html.
You don't have to worry about the HTML template - a designer will care of that - but we do need someone to keep duplication between the reports to a bare minimum.


## Acknowledgement
***
ASSIST acknowledges the importance of open source and the Open Source Community. We make use of free and open-source software during the creation of this exercise. Open source software allows us to create better products and ultimately provide better service for our customers worldwide.  We would like to thank the following Open Source Projects: [SupermarketReceipt-Refactoring-Kata](https://github.com/emilybache/SupermarketReceipt-Refactoring-Kata)
