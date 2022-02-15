# Important Java-Script-Topics

## 1 Variables

### Variable means its can carry something . that can be changeabe,  can be not changeable . 
### There are 4 kind of variable named: 1. Var , 2. Let , 3. Const. 
```
 var,let are changeable Variable. Example ,,,,,

var potato= 20;
var tomato= 30;
let banana= 50;
let totalPrice= potato + tomato + banana
console.log(totalPrice)

 Ans will be 100;

 Const mean Constant If variable declare by [const] . then the value will be constant and can not be changed. Example ,,,,

const potato= 20;
const tomato= 30;

let totalPrice= potato + tomato + banana
console.log(totalPrice)

now the potato and tomato is constant variabel . further the value can not be changed

```
## 2 . Condition
### Condition used in different action for different desicion .
### There have 6 type of Condition : < , > , ===, != , <= , >= .
### Multiple Condition : && = all are true , || = only one is true 
### There have 3 types of conditional statement . if ,  else , else if ,  
#### Not its time to see some example ;

```
const season="winter"
const weather = "Cold"

if (season === "winter" && weather === "Cold") {

    console.log("Now it's 8am now and the sun not yet risen , you can sleep ")

} else if (season !== "winter" && weather === "Cold") {

    console.log("Now it's 8am now and the sun not yet risen for bad weather, you can sleep ")

} else {
    console.log("Now it's 8am now , wakeup and go to school  ")
}

```
## 3 Array
### Array is very special variable in javascript which hold more than one value.

```
const numbers=[10,20,30,40,50,60,70,80,90]
const length=numbers.length
console.log(length)

```
## 4 Loop
### loop is used for run a code over and over again with a different value. loop is commonly used for deal with array.
```
const numbers=[10,20,30,40,50,60,70,80,90]
for (i=0; i < numbers.length; i++) {
    const number = numbers[i]
    console.log(number)
}
```
## 5 Function

### Function is really import in programming language . function basically do 'data in' then 'process the data' then 'return result'
#### For example we can write a simple function;

```
function Student(math, english, physics, Chemistry) {   // Data in
    const sum = math + english + physics + Chemistry    // Data Process
    return sum                                          // return result
}

const result = Student(10, 20, 30, 10)
console.log(result)

we can use loop in the function also

function numberLength(len) {
    const numbers = [10, 20, 30, 40, 50, 60, 70, 80, 90]
    for (i = len; i < numbers.length; i++) {
        const number = numbers[i]
        console.log(number)
    }
}

const result = numberLength(5)

````
## 6 Object in Java-Script
### In real life everything we have seen all are one kind of Objects . Objects are variables too. But objects can contain many values. 

```
const Student = {
    name: "Monna",
    age: 23,
    dresses: ["shirt", "pants", "shoes", "bag"]
}
```

### 3 ways to access Object property

 1. direct via property
 2. accessed via property age String
 3. accessed via property dress in a variabl

```
const Student = {
    name: "Monna",
    age: 23,
    dresses: ["shirt", "pants", "shoes", "bag"]
}
const dress='dresses'
console.log(Student.name)   // direct via property
console.log(Student['age']) // accessed via property age String
console.log(Student[dress]) // accessed via property dress in a variable

```

