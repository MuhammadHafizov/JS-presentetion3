
# JS SCOPE
![](https://cdn.hashnode.com/res/hashnode/image/upload/v1677792599685/cb6ef656-aa26-4d23-9dd6-8767c674192e.png)
+ ## Slide 2: Introduction to Scope 
## Definition of Scope: Scope determines the accessibility of variables, functions, and objects in some particular part of your code during runtime.
## Importance of Scope: Understanding scope is crucial for debugging and writing clean, efficient code.
+ ## Slide 3: Types of Scope in JavaScript 
## Global Scope
## Variables declared outside any function or block.
## Accessible from anywhere in the code. 
## Slide 4: Global Scope Detailed
## Characteristics:
## Created when the script first loads.
## Variables declared in global scope are properties of the window object (in browsers).
## Risks: 
## Risk of variable name collisions.
## Can lead to hard-to-maintain code.
## Slide 5: Function Scope Detailed
## Characteristics:
## Created whenever a function is invoked.
## Variables are accessible only within the function and its nested functions.
## Slide 6: Block Scope Detailed
## Characteristics:
## Introduced with let and const in ES6.
## Restricted to the block in which it is defined.
# JS HOSTING
![](https://iotvnaw69daj.i.optimole.com/cb:mLvy.66914/w:auto/h:auto/q:90/f:best/https://wpshout.com/wp-content/uploads/2019/06/best-nodejs-hosting.jpg)
## Slide 2: Introduction to Hoisting
## Definition: Hoisting is JavaScript’s behavior of moving declarations to the top of their containing scope during the compile phase.
## Slide 3: How Hoisting Works
## Compilation Phase: JavaScript engine scans the code and moves declarations (variables and functions) to the top.
## Execution Phase: Code is executed line by line with declarations already in place.
## Slide 4: Hoisting of Variable Declarations
## var Declaration:
## Hoisted to the top of the function or global scope.
## Slide 5: Hoisting with let and const
## let and const Declarations:
## Hoisted to the top of the block scope.
## Do not get initialized, leading to a "temporal dead zone" until their actual declaration is encountered.
# JS TDZ
![](https://media.licdn.com/dms/image/C4E12AQE2e5VhZp7x7A/article-cover_image-shrink_720_1280/0/1618408334842?e=2147483647&v=beta&t=P9U_JdJdrNNNz_8pCRVSfjEc8_68_mbn1_OOMc4FjgU)
## Slide 2: Introduction to TDZ
## Definition: Temporal Dead Zone (TDZ) refers to the period within a block where a variable is in scope but cannot be accessed until it is declared.
## Relevance: Helps avoid accessing variables before they are fully initialized, leading to more predictable code.
## Slide 3: Variable Declarations and Hoisting
## Hoisting Basics: Variables declared with var are hoisted to the top of their scope, while let and const are also hoisted but come with a TDZ. 
## Slide 4: TDZ with let and const
## let and const:
## Hoisted: Declarations are hoisted to the top of their block scope.
## TDZ: Accessing the variable before its declaration results in a ReferenceError.
![](https://akm-img-a-in.tosshub.com/indiatoday/images/story/202112/kevin-butz-6hsfmat-t7k-unsplas_1200x768.jpeg)
