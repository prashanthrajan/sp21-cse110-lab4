# Part 1a
1) values added: 20
2) values added: 20
3) values added: 20
4) Reference error because the result variable only exists in the if block
5) Error because const variables cannot be reassigned
6) Error because the result variable only exists in the if block, but the code will break earlier because const variables cannot be reassigned and 

# Part 1b
1) 3. The variable i still stores the value it had when it exited the for loop. It is still reachable since it was declared with the 'var' keyword
2) 150. This variable still stores the last discounted price which was 300 at a discount of 0.5 which is 150. This variable is still reachable since it was declared with the 'var' keyword
3) 150. This variable stores the last discounted price that was multiplied by 100, rounded, then divided by 100. This is half of 300 rounded to two decimal places which is 150.
4) [50, 200, 300] This function returns an array of discounted prices. In this case specifically, the prices [100, 200, 300] at a 50% dicount.
5) Reference error because the variable 'i' will have gone out of scope by line 12. This variable only exists in the for loop block (lines 6-10) since it was declared with the 'let' keyword.
6) Reference error because the variable 'discountedPrice' will have gone out of scope by line 13. This variable only exists in the for loop block (lines 6-10) since it was declared with the 'let' keyword.
7) 150. This variable stores the last discounted price that was multiplied by 100, rounded, then divided by 100. This is half of 300 rounded to two decimal places which is 150. The variable, declared with the 'let' keyword, will still be in scope since it wasn't declared in any sub blocks within the function.
8) [50, 200, 300] This function returns an array of discounted prices. In this case specifically, the prices [100, 200, 300] at a 50% dicount. The array 'discount' was not declared in any sub-blocks so it is still in scope. Also, none of the variables declared with 'let' are referenced out of scope so there aren't any Reference Errors.
9) Reference error because the variable 'i' will have gone out of scope by line 11. This variable only exists in the for loop block (lines 6-10) since it was declared with the 'let' keyword.
10) 3. It will print the length of the prices array which in this case is 3. length is declared with the const keyword and it is never modified and it was not declared within any sub-blocks so we do not run into any errors here.
11) [50, 100, 150]. The function works as intended, giving the prices listed after applying the discount. The variables discounted and length are never referenced out of scope. Although we modify discounted, we never reassign it so that does not lead to errors. Within the for loop, it might seem that we are reassigning the const discountedPrice variable, however, we just create a new one each time the loop runs again from the top.
12) Objects  
A) student.name;  
B) student["Grad Year"];  
C) student.greeting();
D) student["Favorite Teacher"].name;  
E) student.courseLoad[0];  
13) Arithmetic  
    A) '32' because the first input is a string so this operation is concatenating strings. The number 2 gets converted to its string equivalent '2' and concatenated to '3' to get '32'  
    B) 1  because the '-' operation is a mathematic operation, node converts the '3' to its numeric equivalent 3 and does the operation 3 - 2.  
    C) 3  since 3 is a number, the '+' is a mathematical operation here, so null is converted to its mathematical equivalent 0 and added to 3.  
    D) '3null'  since '3' is a string, '+' is a string concatenation operation, so null is treated as a string literal and concatenated to '3' to get '3null'  
    E) 4  since 3 is a number, the '+' is a mathematical operation here, so true is converted to its mathematical equivalent 1 and added to 3.  
    F) 0  the '+' is a mathematical operation here, so false is converted to its numeric equivalent of 0, null is also converted to its numeric equivalent of 0, and they are added to each other for a final answer of 0.  
    G) '3undefined'  since '3' is a string, '+' is a string concatenation operation, so undefined is treated as a string literal and concatenated to '3' to get '3undefined'  
    H) NaN  because the '-' operation is a mathematic operation, node converts the '3' to its numeric equivalent 3 while undefined is converted to its numeric equivalent NaN. 3 - NaN results in NaN  
14) Comparison  
    A) True. JS converts the values to numbers so this is the same as 2 > 1  
    B) True. JS converts the values to numbers so this is the same as 2 < 12  
    C) True. JS converts the values to numbers so this is the same as 2 == 2  
    D) False. === is a strict equality check which means JS does not do the usual type conversion. Since '2' and 2 are of different types, they are not exactly the same so this evaluates to false.  
    E) False. JS converts true to its numeric value of 1. So, this isequality is the same as 1 == 2 which is false.  
    F) True. Since the Boolean(2) returns true since 2 is not an "empty" value. This equality is asking if true strictly equals true which is true.  
15) "==" is a regular equality which means that JavaScript is going to convert the values being compared to their numeric equivalents. "===" is a strict equality which means that JavaScript compares the values without doing any type conversion. "===" only returns true if the two quantities are of the same type and value.   