1. The bug was that when doing .value, that gets a string which makes it concatenation. 

2. I would fix it by converting it to numbers by doing Number(num1) + Number(num2) so that it gives the sum. 