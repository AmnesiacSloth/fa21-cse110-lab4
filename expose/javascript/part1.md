1. Line 9 prints the sum of given parameters num1 and num2 - values added: 20
2. Line 13 prints - final result: 20
3. Line 9 prints - values added: 20
4. Line 13 causes an error because of the keyword let. Since let is block scoped this means that after the braces {} then our program can no longer access the variable result.
5. Line 9 causes an error because const variables have to be declared and initialized at the same time. They also cannot be reassigned once initialized.
6. Line 13 causes an error because const variables are also block scoped and therefore once line 13 is reached then the variable result is no longer accessible.
##Part 2
1. Line 12 will print 3 since var variables are global/function scoped 
2. Line 13 will print 150 since it will be assigned the value computed on the final loop and var variables are global/function scoped
3. Line 14 will print 150 since it will be asigned the value computed on the final loop and var variables are global/function scoped.
4. The function will return a filled array with the values computed in the function's for loop.
5. Let is block scoped so line 12 will cause an error because i is no longer defined at line 12
6. Line 13 will cause an error because discountedPrice is no longer defined since it was declared with the let keyword.
7. Line 14 will print 150 since it will be assigned the value computed in the function's for loop and the console.log is within the same scope as where finalPrice was created.
8. The function will return a filled array [50,100,150] because even though discounted was declared with the let keyword since it is returned it must retain the values stored in it by the function.
9. Line 11 will error because i was declared with the let keyword and calling console.log on i is out of scope once the for loop concludes.
10. Line 12 will print 3 because length was declared with the const keyword and it is still within scope at line 12. 
11. The function will return the array [50,100,150] because after the values are inserted then the array as a whole is returned and persists after the function call.
