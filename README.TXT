22. This is what's printed:

    Testing the addition operation.
    The result is: 7
    Testing the subtraction operation.
    The result is: 5
    All tests passed.
    
    Yes, i believe the final line because the only methods to test are the plus and minus in the 
    CalEngineTester class
    
23. The givin result is 1 which is not the same as the printed result
    When called a second time it returns 7
    it should always return the answer 7
    
24. When done with the minus the value drops to 5 then to -13

26. method called: numberPressed(4)
    displayvalue: 4 
    leftOperand: 0 
    previousOperator: ' '
    
    method called: equals()
    displayvalue: 4 
    leftOperand: 0 
    previousOperator: ' '
    
    method called: getDisplayValue()
    displayvalue: 4 
    leftOperand: 0 
    previousOperator: ' '
    
28. method called: clear()
    displayvalue: 0 
    leftOperand: 0 
    previousOperator: ' '
    
    it is in the same state as the previous clear
    
29. we can make one field called result then in the constructor we initialize it to 0 and for example we can change the plus method to result += value; and value would be a
    value we enter in the parameter.
    
30. i cant run this with my version but the previous version works
    
    clear() : resets everything
    numberPressed(9): displayValue: 9
    plus(): 9 "+" 
    numberPressed(1): displayValue: 1
    minus(): 9+1 "-" 
    numberPressed(4) — displayValue: 4
    equals(): calculates 9+1-4=6
    
    yes the answer appears correctly