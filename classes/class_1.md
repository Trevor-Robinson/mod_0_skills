Class: Sandwich

Attributes:  
bread_type (string)  
meats (array)  
cheeses (array)  
veggies (array)  
has_mayo (boolean)  
has_mustard (weight)  
hot (boolean)  
size (string)  


Methods:  
toast (changes hot to true)  
add_mayo (changes has_mayo to true)  
add_mustard (changes has_mustard to true)  
add_meat (appends a meat item to the meats array)  
add_cheese (appends a cheese item to the cheeses array)  
add_veggie (appends a veggie item to the veggies array)  
change_bread (changes the bread_type attribute)  
change_size (changes the size attribute and adds a second instance of each item in the meats array, the cheeses array, and the veggies array)  
make_vegan (remove all items from the meats array and the cheeses array)  
