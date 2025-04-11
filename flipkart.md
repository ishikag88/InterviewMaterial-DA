Flipkart Interview experience- ctc (15-20) lpa

1. Identify users who purchased the same product more than once.

Tables:
orders(order_id, user_id, product_id, order_date)

2. Get the top 5 most returned products by count.

Tables:
returns(return_id, order_id, return_date)
orders(order_id, product_id)

3. Calculate monthly GMV (Gross Merchandise Value).

Tables:
orders(order_id, product_id, user_id, order_date, quantity, price)

4. Find the conversion rate of users (users who added to cart vs those who placed an order).

Tables:
cart_actions(user_id, product_id, action_type, action_time)
orders(order_id, user_id, product_id, order_date)

(Note: action_type = 'add_to_cart', 'remove', etc.)

5. List the top-selling category in each month.

Tables:
orders(order_id, product_id, order_date)
products(product_id, category)


6. Detect users who ordered from 3 or more different categories in a single month.

Tables:
orders(order_id, user_id, product_id, order_date)
products(product_id, category)
