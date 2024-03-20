# Assignment: Calculate Discount Function

## Description

In this assignment, you are required to create a Python function named `calculate_discount` that calculates the final price after applying a discount to an item's original price. The function will take two parameters: `price` (the original price of the item) and `discount_percent` (the percentage of discount to be applied). If the discount percentage is 20% or higher, the discount will be applied; otherwise, the original price will be returned.

After defining the `calculate_discount` function, you should use it to prompt the user to enter the original price of an item and the discount percentage. Then, print the final price after applying the discount, or if no discount was applied, print the original price.

## Function Definition

Create a function named `calculate_discount` with the following signature:

```python
def calculate_discount(price, discount_percent):
    """
    Calculates the final price after applying a discount.

    Args:
        price (float): The original price of the item.
        discount_percent (float): The percentage of discount to be applied.

    Returns:
        float: The final price after applying the discount, or the original price if no discount was applied.
    """
    
