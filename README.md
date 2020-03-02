# What-I-Learned-Week-6

for of loop- good for loops that goes through the whole array or string.
sample setup 

const makeFriendly = function(para){
  let result = ''
  for (const string of para){
    if (string !== '.')
    {result += string}
    else {result += '!'}
  }return result
}

const a variable to be the function can avoid it being changed later

use Math.abs() to find the absolute value of the number

use .startsWith() to check if start with

