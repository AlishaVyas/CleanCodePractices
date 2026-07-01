1. never write function name a noun or adjective
2. use verbs or action in the naming eg: fetchProduct, createProduct
3. keep consistent the naming in the entire code base, like fetchUser, fetchProduct not getProduct
4. give as less parameter as possible max 2 is okay (coz u need to maintain the order wile calling the method)
5. so instead pass one object that contain all the parameter
6. Return early as possible
7. avoid boolean flags in function (don't pass boolean values in functions, coz it creates confusion)
8. single level of abstraction 
9. function name should tell stories