# factorial-function
function factorial(n) {  
     
    if (n < 0) {  
        console.log("Invalid input: Negative numbers do not have a factorial.");  
        return;  
    }  
   
    if (typeof n !== 'number') {  
        console.log("Invalid input: Please enter a number.");  
        return;  
    }  
    
    if (n === 0) {  
        return 1; // 0! = 1  
    }  
    return n * factorial(n - 1); 


console.log(factorial(5));  
console.log(factorial(-1)); 
console.log(factorial("a")); 
console.log(factorial(0));  
