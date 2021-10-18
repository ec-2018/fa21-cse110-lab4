1. '3' is printed to the console, The variable i was declared with function scope and since it is printed after the for loop it holds the same value as the length of the input array.
2. '150' is printed to the console, The variable discountedPrice was declared with function scope and since it is printed after the for the loop it still holds the last value in the output array.
3. '150' is printed to the console, the finalPrice variable holds the same value as the discountedPrice variable here because 300 is cleanly divided in half without any partial cents. 
4. The function returns a length 3 array containing [50, 100, 150]. This function takes an input array and returns an output where it's elements are discounted by the discount input value. 
5. The function throws an error because the i variable is only available in the scope of the for loop. 
6. The function throws an error because the discountedPrice variable is only available in the scope of the for loop.
7. '150' is printed to the console, the finalPrice variable is declared at the top level of the function so it's available within the scope of the function. 
8. The function will return the same array as in question 4 because every time a variable is used in this function it was declared either in the same scope or a greater one. Thus, changing all var declarations to let declarations will not have an effect on the outcome of the function. 
9. The function throws an error because the i variable is only available in the scope of the for loop. 
10. '3' is printed to the console, the length variable is set equal to the length of the prices array and a const cannot be changed 
11. The function returns a length 3 array containing [50, 100, 150]. The function works similarly to the other two versions except the discounted price is calculated once per loop and push onto the array without rounding. The const variable inside the for loop is redeclared and assigned every loop so it does not cause an error. 
12. 
    - student['name']
    - student['Grad Year']
    - student['greeting']()
    - student['Favorite Teacher']['name']
    - student['courseLoad'][0]
13. 
    - '32': 2 is converted to a string and concatenated with 3
    - 1: '3' is converted to a number and 2 is subtracted from it
    - 3: null is converted to 0 and added to 3
    - '3null': null is converted to 'null' and concatenated to '3'
    - 4: true is converted to 1 and added to 3
    - 0: false and null are both converted to 0 and added together
    - '3undefined': undefined is converted to 'undefined' and concatenated with '3'
    - NaN: The answer is not a number
14. 
    - true: '2' is converted to 2 
    - false: '2' has a higher lexicographical weight in the first position than '12'
    - true: '2' is converted to 2
    - false: 2 and '2' are different types so are not strictly equal 
    - false: true is converted to 1 
    - true: Boolean(2) is converted to true
15. The == operator will try to do type conversion while the === operator will return false if comparing different types. 
16. (In separate file)
17. The function returns an array [2, 4, 6]. The function iterates over the items in the array an call the callback function on each element. The callback function doubles each element. 
18. (In separate file)
19. 1 4 3 2 
