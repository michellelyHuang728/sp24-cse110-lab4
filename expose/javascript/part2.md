Question 1:
The function will log 3 to the console. Because "i" is declared with "var" keyword which has a global scope. i is incremented in the for loop by three times because the length of prices array is 3. 

Question 2:
150 will be log to the console as "result" is a global variable and it will be reassigned for each iteration in taht for loop. When i=2, 300*(1-0.5)=150.

Question 3:
150 will be log to the console. finalPrice is a global variable declared as a "var" variable. it will be reassigned for each iteration in that for loop. When i=2, 300*(1-0.5)=150. Then final price=Math.round(150 * 100) / 100 = 150.0.

Question 4:
It will return [50, 100, 150]. When i=0, original price=100. Discount calculation is 100 * (1 - 0.5) =50. Final price is Math.round(50 * 100) / 100 = 50. When i=1, original price is 200, discount calculation is 200 * (1 - 0.5) = 100. Final price is Math.round(100 * 100) / 100 = 100.00. When i=2, 300*(1-0.5)=150. Then final price=Math.round(150 * 100) / 100 = 150.0.

Question 5:
It will return an error as "i" is declared within the for loop with "let".

Question 6:
It will return an error as "discountedPrice" is declared within the for loop. It will not be accessible outside of the for loop.

Question 7: 
It will log 150 to console as finalPrice is decared within the function loop with "let" so it is accessible. it will be reassigned for each iteration in taht for loop. When i=2, 300*(1-0.5)=150. Then final price=Math.round(150 * 100) / 100 = 150.0.


Question 8:
It will return [50, 100, 150]. When i=0, original price=100. Discount is declared with "let" and is called within the scope of function. Discount calculation is 100 * (1 - 0.5) =50. Final price is Math.round(50 * 100) / 100 = 50. When i=1, original price is 200, discount calculation is 200 * (1 - 0.5) = 100. Final price is Math.round(100 * 100) / 100 = 100.00. When i=2, 300*(1-0.5)=150. Then final price=Math.round(150 * 100) / 100 = 150.0.


Question 9:
The console will log an error because variable "i" is declared with "let" within the for loop and the scope is limited to the for loop, which is not accessible outside the loop.

Question 10: 
The console will log 3 as the length of prices is 3.

Question 11:
It will return [50, 100, 150]. When i=0, original price=100. Discount is declared with "let" and is called within the scope of function. Discount calculation is 100 * (1 - 0.5) =50. When i=1, original price is 200, discount calculation is 200 * (1 - 0.5) = 100. When i=2, 300*(1-0.5)=150. Even though discount is constant, but we are always refering to the same array that initially being assigned to "discount". Also, for discountPrice, each for loop is a new scope and the discountPrice will be recreated. So even if discount and discountPrice are constant variable, it won't cause any issue.

Question 12:
A: student.name;
B:student['Grad Year'];
C:student.greeting();
D:student['Favorite Teacher'].name;
E:student.courseLoad[0];

Question 13:
A. '32'
B. 1
C. 3
D. '3null'
E. 4
F. 0
G. '3undefined'
H. NaN

Question 14:
A. true
B. false
C. true
D. false
E. false
F. true

Question 15:
The difference between them is how they handle type coercion during comparison. == compares two values after converting both to a common type if their type are not the same. === won't convert both to a common type, it will just compare directly. 

Question 17:
The result will be [2,4,6]. modifyArray takes in two argument:array and callback, where array here is [1,2,3] and callback here is the function "doSomething". In function modifyArray, the for loop will iterate through the array and apply the doSomething function on each element and put this in newArr. So each element in [1,2,3] will be apply to doSomething, which times each element with 2. So it returns newArr [2,4,6].

Question 18:
"1","4", "3", "2"
The first line "console.log(1)" prints 1, then the fourth line"console.log(4)" prints 4. Then the third line prints "3" after 0 second delay.. the second line print "2" after 1 second.




