# Lab 4 Part 1
1. The size of prices will be printed, since `var` is not block scoped.
2. The last discounted price will be printed, since `var` is not block scoped.
3. The last final price will be printed, since `var` is not block scoped.
4. The function will return `[50, 100, 150]`, as expected.
5. An error will occur, since, `i` is not defined at line 11.
6. An error will occur, since `discountedPrice` is not defined at line 12.
7. Assuming the previous two errors were fixed, the final price of the last item will be printed, since it scoped to the function, not the for loop.
8. It will not return since an error will occur due since line 11 is trying to print out a variable which does not exist in it's scope.
9. An error will occur since i is not defined at line 11
10. An error will occur since discountedPrice is not defined in this scope.
11. 0 will be printed since const cannot be updated.
12. The function will return `null` since there are runtime errors due to unassigned variables and trying to update const values.
13. 	a. student.name
	b. student["Grad Year"]
	c. student.greeting()
	d. student["Favorite Teacher"].name
	e. student.courseLoad[0]
14.	a. 32 - string concatenation
	b. 1 - automatic type conversion
	c. 3 - null is converted to 0
	d. 3null - string concatenation
	e. 4 - automatic type conversion, true = 1
	f. 0 - automatic type conversion, false = 0, null = 0
	g. 3undefined - string concatenation
	h. NaN - attempted automatic type conversion
15.	a. true, automatic conversion to numbers
	b. true, automatic conversion to numbers
	c. true, automatic conversion to numbers
	d. false, strict equality, no automatic conversion
	e. false, automatic conversion of true to 1
	d. true, Boolean(2) = true
16. The equality (==) operator compares to javascript variables, converting them to numbers if they are of different types. The strict equality operator(===) compares them without converting to numbers
17. "How are you?" gets printed since 2 != true, and 2 evaluates to true.
19. The result will be [3, 8, 10], since evaluating the stack of callbacks will first add 2 to the array values, then multiply them by 2.
21. The output will be 1, 3, 4, 2
