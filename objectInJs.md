# different way to create object in Js

# 1 Using object literal
![image](https://user-images.githubusercontent.com/44174633/183815123-525440db-8c60-4d80-80a0-2d2456ebdfd8.png)
![image](https://user-images.githubusercontent.com/44174633/183815257-b5459b6d-80cb-4b96-9bab-9dc4ae1c9a83.png)
![image](https://user-images.githubusercontent.com/44174633/183815319-b171962f-d43d-4c34-b466-39d52e66297d.png)
* You can create an object using an object literal. An object literal uses { } to create an object directly.
* An object is created with a key:value pair.
* You can also define functions, arrays and even objects inside of an object.

# Create an Object using Instance of Object Directly
![image](https://user-images.githubusercontent.com/44174633/183815707-ca3fb9ff-a4c8-4e05-85f3-d30dd0f20cfc.png)
![image](https://user-images.githubusercontent.com/44174633/183815738-315edab2-9ca9-4486-8e29-e819813d4200.png)
* Here, the new keyword is used with the Object() instance to create an object.

# Create an object using Constructor Function.
![image](https://user-images.githubusercontent.com/44174633/183816135-bab36f18-6d28-46c1-b6d1-dc7ee4707106.png)
![image](https://user-images.githubusercontent.com/44174633/183816157-4d0104ad-6c9a-47ea-8262-41ef53a9482d.png)
* the Person() constructor function is used to create an object using the new keyword.
* new Person() creates a new object.

note: * we cannot use object created with literal with multiple object ,because any change in object will reflect in all the object. 
 * we can create multiple object with constructor function and use where we want , any change in any of objecct will not reflect to any of object because all object have different reference and different storage .
 
 # Adding Properties And Methods in an Object.
 ![image](https://user-images.githubusercontent.com/44174633/183817692-e3c95e08-5c67-4a16-8da6-a09a68cd3891.png)
* here we can see that that the properties and method for person1 and person2 is different.

![image](https://user-images.githubusercontent.com/44174633/183817795-91bcb618-dc8a-458c-b8cc-d508d6256d06.png)

# Note: In JavaScript, the keyword class was introduced in ES6 (ES2015) that also allows us to create objects. Classes are similar to constructor functions in JavaScript. To learn more, visit JavaScript Classes.
 
