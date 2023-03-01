##  :umbrella: Regular Expression Regx :umbrella:

regex literal notation -> /pattern/

      /pattern/modifiers;
      
1.Matching a specific string :

    const regex = /hello/;
    console.log(regex.test("hello world")); // true
    console.log(regex.test("goodbye world")); // false
    
 2.Matching any character:
 
    const regex = /./; // the period matches any character
    console.log(regex.test("hello")); // true
    console.log(regex.test("123")); // true
    console.log(regex.test(" ")); // true
    
 3.Matching a range of characters:
 
    const regex = /[a-z]/; // matches any lowercase letter
    console.log(regex.test("hello")); // true
    console.log(regex.test("123")); // false
    console.log(regex.test("HELLO")); // false
    
4.Matching a digit:

    const regex = /\d/; // matches any digit
    console.log(regex.test("123")); // true
    console.log(regex.test("abc")); // false
    console.log(regex.test("1a2b3c")); // true
    


 

