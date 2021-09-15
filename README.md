# Boolean-Logic-Exercise

Part I

Write down what the following statements will return.

1. 2 == "2"; return true
2. 2 === 2; return true
3. 10 % 3; return 1
4. 10 % 3 === 1; return true
5. false && true; return false
6. false || true; return true
7. true || false; return true

Part II

Answer the following questions about this code block:

let isLearning = true;
if(isLearning){
console.log("Keep it up!");
} else {
console.log("Pretty sure you are learning....");
}

1. What should the above code console.log? "Keep it up!" should appear because the value of the isLearning variable is truthy, thereby, the if statement will be evaluated

2. Why do we not need to specify if(isLearning === true)? Why does if(isLearning) work on its own? The simple answer is, since true is a "truthy" value, a true condition will evaluate into a truthy value

let firstvariable;
let secondvariable = "";
let thirdvariable = 1;
let secretMessage = "Shh!";

if(firstvariable){
console.log("first");
} else if(firstvariable || secondvariable){
console.log("second");
} else if(firstvariable || thirdvariable){
console.log("third");
} else {
console.log("fourth");
}

1. What should the above code console.log? This should console.log "Third". Although the firstVarable is falsey, the thirdVariable is truthy and the or statement is only looking for only one truthy statement.

2. What is the value of firstVariable when it is initialized? The value of firstVariable appeared as undefined because the variable was not assigned any value
35. Is the value of firstVariable a "truthy" value? No it is not a truthy value because undefined is a falsey value

4. Is the value of secondVariable a "truthy" value? No it is not a truthy value because it is an empty string, empty strings are falsey values as well

5. Is the value of thirdVariable a "truthy" value? Yes it is a truthy value because the number is greater than 0, all numbers greater than 0 are truthy

Part III

1. Research Math.random here and write an if statement that console.log's "Over 0.5" if Math.random returns a number greater than 0.5. Otherwise console.log "Under 0.5"

let test= Math.random();
if (test>0.5) {
console.log("over 0.5")
} else {
console.log("under 0.5")
}

2. What is a falsey value? List all the falsey values in JavaScript.
A falsey value is a value that considered false when encountered in Boolean context. in JavaScript falsey values include the following: 0 (Zero), "" (empty string value), false, null (absence of any value), undefined and NaN (not a number).
