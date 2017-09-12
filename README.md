Quize from Udacity
/*
 * Programming Quiz: Converting Tempatures (2-2)
 *
 * Use the Celsius-to-Fahrenheit formula to set the fahrenheit varible:
 *
 *     F = C x 1.8 + 32
 *
 * Log the fahrenheit variable to the console.
 *
 */
// Here is the answer
var celsius = 12;
var fahrenheit = celsius * 1.8 + 32;/* convert celsius to fahrenheit here */

console.log(fahrenheit);

/*
 * Programming Quiz: Out to Dinner (2-10)
 */

// your code goes here
var bill = 10.25 + 3.99 + 7.15;
var tip = (10.25 + 3.99 + 7.15)*0.15;
var total = bill + tip;
console.log(total);

/*
 * Programming Quiz: MadLibs (2-11)
 * 
 * 1. Declare a madLib variable
 * 2. Use the adjective1, adjective2, and adjective3 variables to set the madLib variable to the message:
 * 
 * 'The Intro to JavaScript course is amazing. James and Julia are so fun. I cannot wait to work through the rest of this entertaining content!'
 */

var adjective1 = 'amazing';
var adjective2 = 'fun';
var adjective3 = 'entertaining';

var madLib = `The Intro to JavaScript course is ${adjective1}. `
    + `James and Julia are so ${adjective2}. `
    + `I cannot wait to work through the rest of this ${adjective3} content!`;
    console.log(madLib);
