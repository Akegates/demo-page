1. Variables

var x= 7;
undefined
x
7

var myCar='Cadillac'
undefined
myCar
'Cadillac'

2. Arrays

var myData=[7,'John','Jane',17];
myData
(4) [7,'John','Jane'17]
0:7
1:'John'
2:'Jane'
3:17
length:4

myData [2];
'Jane'

3. Adding elements

Pushing:

myData.push(10)
5
myData
(5) [7,'John','Jane',17,10]

Removing elements

Popping:

myData.pop()
10
myData
(4) [7,'John','Jane',17]

4. Data types

STRING myData='Cars';

NUMBER myData=7;

BOOLEAN 4>3
true

ARRAY myCars=['Ford','Toyota']

OBJECT var person={firstName:'John',lastname:'Doe'}

NULL var name= null

UNDEFINED var name

var x=['John',7];

var a = 7+7
var b = '7'+7
a
14
b
77

var c='Hello'+7
c
'Hello7'

5. Arithmetic Operators

- , - , \* , / , % , var x = 7 ,x++ , var y = 5,y=--

Assignment Operators

= var x = 27;

+= x += y;
x = x + y

-= x -= y;  
 x = x - y

-= x -= y
x = x \* y

6. String Operators

var one='Piros';
var two='Kek';
var three=one+' '+two;
three
'Piros Kek'

var c='Hello';
c+='world!';
c
'Hello world!'

7. Comparison Operators

EQUAL ==
2==2
true

STRICTLY EQUAL ===
4===4
true
'7'===7
false

NOT EQUAL !=
8!=3
true

STRICTLY NOT EQUAL !==
8!=8
true

Greater than <

5>2

> true

Less than <
4<3
false

GREATER THAN OR EQUAL >=
4>=3
true

LESS THAN OR EQUAL <=
3<=4
true

8. Logical Operators

&&: x < 10 && y > 6

||: x < 10 || y > 6

var x=7;
var y=6;

x < 10 && y> 6
false: both statements together are not true

x < 10 || y > 6
true: one of the statements is true

typeof Operator

typeof 'John'
'string'

typeof 7
'number'

typeof false
'boolean'

typeof myCar
undefiened

typeof null
'object'

typeof [1,2,3] <=Array
'object'

9. Conditionals

if(myNum==7){
console.log('Lucky 7!');
}
Lucky 7!
undefined

var myNum=10
undefined
myNum
10
if(myNum==7){
console.log('Lucky 7!');
}else{
console.log('You're not ver lucky today...');
}
You're not ver lucky today...
undefined

10. Functions

function addNum(num1,num2) {
var result= num1 + num2;
return result;
}
undefined
addNum(10,20);
30

11. Comments

Single line comment: //...
Multiple line comment: /_...
...
_/

12. JavaScript Event:

document.querySelector('html').onclick = function() {
alert('Ouch! Stop poking me!');
}
ƒ () {
alert('Ouch! Stop poking me!');
}
