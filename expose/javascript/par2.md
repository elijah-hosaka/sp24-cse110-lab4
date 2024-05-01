1. Line 12 will print `3` because the code iterates through the for loop 3 times and by the time it's done, the value of `i` would be `3`
2. Line 13 will print `150` because at the last iteration of the for loop, `discountedPrice` is getting assigned `prices[2] * (1 - discount)` which is 300 * (0.5) = 150
3. Line 14 will print `150` because `finalPrice` is getting assgined the aforementioned `discountedPrice`, which is 150 in the last iteration of the for loop, times 100, rounded, then divided by 100 which is still 150
4. This function will return the list [50, 100, 150] because the for loop is taking each item in the `prices` list and multiplying them by 0.5 and pushing that to the list `discounted`
5. Line 12 will cause an error because the `let` variable `i` is being referenced outside the scope it was declared in which is the for-loop scope
6. Line 13 wil also cause an error because the `let` variable `discountedPrice` is being referenced outside the scope it was declared in which is the for-loop scope
7. Line 14 will print `150` because the `let` variable `finalPrice` is being referenced inside the scope it was desclared in which is the function scope
8. The funciton will return the list [50, 100, 150] because the `let` variable `discounted` which is getting returns is being referenced inside the scope it was declared in
9. Line 11 will cause an error because the `let` variable `i` is being referenced outside the scope it was declared in which is the for-loop scope
10. Line 12 will print `3` because it's printing the `const` variable `length` which was initially initialized to `prices.length` and `prices` has 3 elements, [100, 200, 300]
11. This function will return the list [50, 100, 150] because all the variables are referenced correctly so the function behaves the same as normal
12. A. student.name  
    B. student['Grad Year']  
    C. student.greeting()  
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0]
13. Arithmetic  
    A. '3' + 2 = '32' because JS maps the integers to their exact string representation and concatenates
    B. '3' - 2 = 1 because JS maps the string to their exact integer representation and subtracts  
    C. 3 + null = 3 because JS treats null as 0  
    D. '3' + null = '3null' because JS converts null to a string and concatenates  
    E. true + 3 = 4 because JS maps true to 1 and adds  
    F. false + null = 0 because JS treats both false and null as 0 in numeric equations  
    G. '3' + undefined = '3undefined' because JS converts undefined to a string and concatenates  
    H. '3' - undefined = Not-a-Number (NaN) because JS can't convert undefined to a valid number
14. Comparison  
    A. '2' > 1 = true because JS converts the string to its number representation and compares  
    B. '2' < '12' = false because JS performs a lexicographical comparison  
    C. 2 == '2' = true because == allows type conversions so the string is converted to its number representation  
    D. 2 === '2' = false because === compares without allowing type conversions and the types don't match  
    E. true == 2 = false because true is mapped to 1  
    F. true === Boolean(2) = true because Boolean(2) is true and both type and value match
15. The difference between the == and === operators is that == checks for equality after doing type conversion and === checks for equality of both value and type
16. In the js file
17. The function will return the list [2, 4, 6] because the for-loop in the `modifyArray` function is calling the method `doSomething`, which multiplies every number by 2, and pushing those numbers into the return array
18. In the js file
19. The output is 1 4 3 2 because 1 and 4 get printed out immediately when called and 3 and 2 get printed after the script ends because of the setTimeout function which is 0ms for 3 and 1000ms for 2