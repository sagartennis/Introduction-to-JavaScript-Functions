# Introduction-to-JavaScript-Functions
Questions on Functions


## Question 1:  Laugh it off - 1
```
Declare a function called laugh() that returns "hahahahahahahahahaha!". Print the value returned from the laugh() function to the console.
```
## Answer 1: 

```
function laugh(){
    var message = "hahahahahahahahahaha!";
    /* the retuen value will hold the message to be printed out in console.log. It will stop executing the function once it sees the return command. */
    return message;

}
console.log(laugh());
```

## Question 2: Laugh it off-2 

```
Write a function called laugh() that takes one parameter, num that represents the number of "ha"s to return.

TIP: You might need a loop to solve this!

Here's an example of the output and how to call the function that you will write:

console.log(laugh(3));
Prints: "hahaha!"
```
## Answer 2: 

```
function laugh(num){
    var laughString = "";
    for(x = 0; x < num; x++ ){
        laughString = laughString + "ha";
    }
    return laughString + "!"

}
console.log(laugh(3));
```
