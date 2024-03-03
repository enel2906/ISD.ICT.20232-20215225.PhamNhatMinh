Basic Flow:

1. The Customer can reviews the items in the shopping cart and decides which ones they like to buy.
2. The Customer can select products their cart to place an order(The system need to update the quantity of the product to help customers know if products are avaiable)
3. The System return the successful notification and customer can view the delivery information form.
4. The Customer can updates delivery information:
      Address
      Recipient name
      Email
      Phone number
5. After calculate, the system will return the outcome for the customer:
      List of products in the cart
      Price
      Quantity
      Total product price (excluding VAT)
      Total product price (including VAT)
      Delivery fee
      Total amount
6. The Customer can update or confirm cancellation if the order has not been delivered to the carrier
7. The Customer selects and provides information for a payment method supported by VNPay.
8. The System processes payment through VNPay.
9. The System displays transaction details.
10. The System sends successful notification for the custommer account.
11. The System records transaction and order information.
12. The Customer receive notification and can track the delivery process.

Alternative Flows:
      1. Invalid Information:
            - System check if the information of customer provide when order are invalid 
            will decline the request and ask customer for re-enter until the information is valid
      2. Invalid Products:
            - The system has flow to check and auto update the quantity of the product.
            - If the product in the cart of the customers are not available, this will make a notification for them to know.
      3. Making Rush Order:
            - On order place customer can select Rush Order.
            - The system will check which products are support Rush Orders.
            - If all the products are support Rush Orders, the system will recalculate orders fee by Rush Order fee.
            - Products that do not support express delivery will be delivered as usual. Fee Delivery will be calculated and 
            displayed separately for normally delivered products (if yes) and fast delivery products.
