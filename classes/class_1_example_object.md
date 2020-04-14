## Object: master_oven3000

### Attributes:
1. cook_type = "conventional"
1. is_on = false
1. temperature = 0
1. is_empty = temperature


### Results
1. calling `convection` changes cook_type to "convection"
1. calling `turn_on`  sets is_on to true
1. calling `set_temp(400)` sets temperature to 400
1. calling `insert_dish` changes is_empty to false
