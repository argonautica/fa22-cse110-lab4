1. values added: 20
2. final result: 20
3. values added: 20
4. Nothing is printed. 

ReferenceError: result is not defined
    at sumValues (<anonymous>:14:32)
    at <anonymous>:17:1
    at dn (<anonymous>:16:5449)

This is because of the fact that result is only defined within the bounds of the if statement, and outside of that block of code it cannot be accessed. 

5. Nothing is printed. The code does not run because we attempt to assign a new value to a variable that is designated to be a "const" after having instantiated it. 

Cannot assign to "result" because it is a constant

6. Same as 5. 

