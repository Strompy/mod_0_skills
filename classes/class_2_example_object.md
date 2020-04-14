## Object: register1

### Attributes:
1. cash_amount = 100
1. is_open = false
1. num_open_orders = 0
1. menu_items = 20


### Results:
1. calling `log_in` changes `is_open` to true
1. calling `place_order` changes `num_open_orders` to 1
1. calling `accept_payment` changes `cash_amount` to 110
1. calling `new_item(sandwich)` adds sandwhich to the `menu_items` array
