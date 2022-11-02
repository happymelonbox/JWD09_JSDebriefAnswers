
# Answers 
  
### 1
let skyColor = "blue";  
let carColor = "blue";  
let hairColor = "black";  
  
console.log(skyColor === carColor);  
console.log(skyColor === hairColor);  
console.log(skyColor !== hairColor);  
  
### 2
x = 6;  
y = 3;  
console.log(x < 10 && y > 1);  
console.log(x == 5 || y == 5);  
console.log(!(x == y));  
  
### 3
let number = 5;  
   
if (number >= 20) {  
 console.log("Your number is greater than or equal to 20.");  
} else {  
 console.log("Your number is less than 20.");  
}  
  
### 4
let a = 10;  
let b = 5;  
if (a > b) {  
 console.log("a is greater");  
} else {  
 console.log("b is greater");  
}  
// a. Try the above using a ternary operator  
a > b ? console.log("a is greater") : console.log("b is greater");  
  
### 5
let month = "December";  
if (month == "December" || month == "January" || month ==   "February") {  
 console.log("It's Summer");  
} else if (month == "March" || month == "April" || month == "May")   {  
 console.log("It's Autumn");  
} else if (month == "June" || month == "July" || month ==   "August") {  
 console.log("It's Winter");  
} else if (month == "September" || month == "October" || month ==   "November") {  
 console.log("It's Spring");  
} else {  
 console.log("Invalid");  
}  
  
### 6
let light = “Red”;  
   
switch (light.toLowerCase().trim()) {  
 case "green":  
   console.log("You should go.");  
   break;  
   
 case "orange":  
  console.log("You should slow down.");  
   break;  
   
 case "red":  
   console.log("You should stop!");  
   break;  
   
 default:  
   console.log("Please enter a valid valor.");  
   break;  
}  
