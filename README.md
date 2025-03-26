"# Refactoring" 
Hello,  
This refactoring was made by Bohdan Horbatiuk,  
a student of Software Engineering,  
3rd course, 343A-1 group.  

## Let's start:  
The standard format for writing code in Java  
We use **Google Java Style**  

1. I believe that every Java class should      
    have its own dedicated place.  
    When working on a big project, the better you "split your code,"  
    the more readable it becomes.  
    So in Main, I want to see everything about Main, without additionl information.
---------------------------------------

2. Class names should follow PascalCase

NO --| humanIMB --> YES --| HumanIMB (Class names should start with an uppercase letter and use PascalCase).
---------------------------------------

3. Variable names should use camelCase

NO --| W, H, imb --> YES --| weight, height, bmi (Instance variables should follow camelCase notation).
---------------------------------------

4. Use && instead of & for logical operations

NO --| if (imb >=18.5 & imb <25) --> YES --| if (bmi >= 18.5 && bmi < 25) (Using && ensures short-circuit evaluation).
---------------------------------------

5. Method and variable names should be meaningful and follow naming conventions

NO --| takeW(), putW() --> YES --| getWeight(), setWeight()

NO --| takeH(), putH() --> YES --| getHeight(), setHeight()

NO --| takeImt() --> YES --| getBmi()

NO --| Result() --> YES --| getBmiCategory()
---------------------------------------