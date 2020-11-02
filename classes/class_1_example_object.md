Object: ChickenClub

Attributes:
bread_type: "Sourdough"
meats: ["chicken", "bacon", "ham"]
cheeses: ["cheddar"]
veggies: ["lettuce", "tomato"]
has_mayo: true
has_mustard: false
hot: true
size: "medium"

Methods:

toast: hot already = true, no change occurs
add_mayo: has_mayo already = true, no change occurs
add_mustard: has_mustard = true
add_meat: meats =["chicken", "bacon", "ham", "turkey"]
add_cheese: cheeses = ["cheddar", "swiss"]
add_veggie: veggies = ["lettuce", "tomato", "onion"]
change_bread: bread_type = "White"
change_size: size = "large"
             meats = ["chicken", "chicken", "bacon", "bacon", "ham", "ham", "turkey", "turkey"]
             cheeses = ["cheddar", "cheddar", "swiss", "swiss"]
             veggies = ["lettuce", "lettuce", "tomato" "tomato", "onion", "onion"]
make_vegan: meats[]
            cheeses[]
            veggies["lettuce", "lettuce" "tomato", "tomato", "onion", "onion"]
