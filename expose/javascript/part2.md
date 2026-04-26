1. The code prints "3" because var makes it global so it is within scope
2. The code prints "150" because var makes it global so it is within scope
3. The code prints "150" because var makes it global so it is within scope
4. The code returns an array with the numbers of the discounts applied to the original numbers. 
In this case it would return the array [ 50, 100, 150 ]

5. This results in an error because i is not defined in that scope, it is only defined within the for block
because of the let keyword
6. This results in an error because discountedPrice is within the for block with the let keyword so it in not
in scope of the console.log
7. The code prints "150" since the variable was defined in the function scope
8. The code returns an array with the numbers of the discounts applied to the original numbers. 
In this case it would return the array [ 50, 100, 150 ]
9. This results in an error becuase we are attempting to push values into an array that is already set by the const keyword so line 11 is not reached. 
10. This results in an error becuase we are attempting to push values into an array that is already set by the const keyword so line 12 is not reached. 
11. This results in an error becuase we are attempting to push values into an array that is already set by the const keyword so the function does not reach the return statement. 

12. 
a. student.name
b. student['Grad Year']
c. student.greeting()
d. student['Favorite Teacher'].name
e. student.courseLoad[0]

13. 
a. '32', adding a number and a string makes a string
b. 1, subtracting a number from a string that is a number makes a number
c. 3, null is treated as zero when adding to a number
d. '3null', null becomes treated as a string when added to a string
e. 4, true is treated like 1 when adding a number
f. 0, false and null are both treated like the number 0 when adding
g. '3undefined', undefined is treated as a string when added to a string 
h. NaN, undefined is treated as a value when subtracting so it makes the number NaN

14. 
a. true, 2 becomes treated like a number and 2 is greater than 1
b. false, based on Unicode so '1' in 12 is compared to '2' in the dictionary
c. true, '2' gets coverted to a number and 2 does equal 2 so true
d. false, they are not the same type
e. false, true is equal to 1 in javascript
f. true, Boolean treats any number that is not 0 as true

15. 
== is checking loosely for equality in a way that makes sense in conversion of types. === is checking strictly that things are the same type and same value foe equality. 

16. 
for(let car in statistics){
    let value = statistics[key];

  if (key.startsWith("r") || value % 2 !== 0) {
    console.log(value);
  }
}

17. the result will be that whatever the callback does will be applied to the array. In this case, we call the function doSomething to be our callback and doSomething multiplies a number by 2. Since we did a loop on the array with the callback as doSomething, each number in the array will be multiplied by 2. 

18. did it

19. The output is 
1
4
3
2