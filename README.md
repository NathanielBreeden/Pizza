# Pizza
Class Pizza {
private $topping;
private $diameter;
private $price;

function setTopping ($topping) {
     $this->topping - $topping;
}
function getTopping() {
     return $this->topping;
}
function setDiameter ($diameter) {
     $this->diameter - $diameter;
}
function getDiameter() {
     return $this->diameter;
}
function setPrice ($price) {
     $this->price- $price;
}
function getPrice() {
     return $this->price;
}






Print “Would you like a  pepperoni or cheese pizza?”
If pepperoni is entered 
     set pizza to pepperoni
If cheese is entered 
     set pizza to cheese
 Else
     Print “I’m sorry that is not an option.”

Print “Do you want a 12-in., 14-in., or 15-in. diameter pizza?”
If 12 is entered
     set diameter to 12
     set price to 13.99
if 14 is entered
     set diameter to 14
     set price to 16.99
if 15 is entered
      set diameter to 15
      set price to 19.99 

Print “Would you like a  second pepperoni or cheese pizza?”
If pepperoni is entered 
     set secondPizza to pepperoni
If cheese is entered 
     set secondPizza to cheese
 Else
     Print “I’m sorry that is not an option.”

Print “Do you want a 12-in., 14-in., or 15-in. diameter pizza?”
If 12 is entered
     set secondDiameter to 12
     set secondPrice to 13.99
if 14 is entered
     set secondDiameter to 14
     set secondPrice to 16.99
if 15 is entered
      set secondDiameter to 15
      set secondPrice to 19.99 
Print “Would you like a  third pepperoni or cheese pizza?”
If pepperoni is entered 
     set thirdPizza to pepperoni
If cheese is entered 
     set thirdPizza to cheese
 Else
     Print “I’m sorry that is not an option.”

Print “Do you want a 12-in., 14-in., or 15-in. diameter pizza?”
If 12 is entered
     set thirdDiameter to 12
     set thirdPrice to 13.99
if 14 is entered
     set thirdDiameter to 14
     set thirdPrice to 16.99
if 15 is entered
      set thirdDiameter to 15
      set thirdPrice to 19.99 
set totalPrice to price + secondPrice + thirdPrice
print “ You have ordered one (diameter) (pizza), one (secondDiameter) (secondPizza), and one (thirdDiameter) (thirdPizza). Your total is (totalPrice)
