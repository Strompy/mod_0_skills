## Class: point_of_sale

### Attributes:
1. cash_amount (integer)
1. is_open (boolean)
1. num_open_orders (integer)
1. menu_items (array)


### Methods:
1. accept_payment (accepts payment from customer modifies `cash_amount`)
1. log_in (server logs in and opens POS changing `is_open`)
1. place_order (place customer order and changes num_open_orders)
1. new_item (adds a new menu item, adding it to the menu_items array)
