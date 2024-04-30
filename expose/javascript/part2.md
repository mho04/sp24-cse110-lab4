It prints 3 because var isn't block scoped but rather function or global scoped and line 12 is after the loop. The function is called with 3 prices, so the loop will run 3 times resulting in i being 3.
It prints 150 because that is half of 300, the last element in the array to discount.
It prints 150 for the same reasoning as line 12 and 13.
The function will return an array with 3 elements [50, 100, 150] after each element goes through the loop and is discounted give percentage, 0.5.
ERROR, because the i can only be accessed within the for loop.
ERROR, because discuontedPrice was declared within the for loop block hence it can only be used within that block
It prints 150, finalPrice was declared in the same block as line 14 hence it can be accessed by it.
The function will return  an array with 3 elements [50, 100, 150] because the for loop accessing discounted and finalPrice is within their block.
ERROR, i is not within line 11's block scope
Its prints 3 because thats the amount of prices passed through the function and stored into length
An array [50, 100, 150], none of the const variables are changed after declaration. discountedPrice's each time the loop runs is redeclared hence isn't technically being intialized to something else.
-----
12a) student.name
  b) student['Grad Year']
  c) student.greeting()
  d) student['Favorite Teacher'].name
  e) student.courseLoad[0]
-----
13a) '32'
  b) 1
  c) 3
  d) '3null'
  e) 4
  f) 0
  g) '3undefined'
  h) NaN
-----
14a) true
  b) true
  c) true
  d) false
  e) false
  f) true
-----
15) == preforms a type conversion before comparing while === does not which is why 2 === '2' is false while 2 == '2' is true
