As per as the test doc given by your site , i have done the code and wrote the test cases

in folder attached on documents there is 2 folder one is 'src' and 2nd one is 'tests'

tests folder contains testcases and src folder contains actual application code

** PART.1-Test cases** You can execute 9 test cases by hiting this command on terminal ./vendor/bin/phpunit --testdox tests

Like this **

PS C:\xampp\htdocs\test> ./vendor/bin/phpunit --testdox tests

PHPUnit 6.5.0 by Sebastian Bergmann and contributors.

Data
 [x] Question Format -If you buy 5 ‘C’s you would get 2 for 38 + 3 for 
 
 [x] Question Format -If you buy 4 ‘C’s you would get 3 for 50 + 1 for 20
 
 [x] Question Format -if you buy 10 ‘D’s and 6 ‘A’s, 6 of the ‘D’s will cost 5 each whilst the other 4 will cost 15
 
 [x] check single sku with price -This will Check amount is valid or not for single SKU(A) in multiple(3 Unit) buy test
 
 [x] check single sku with price -This will Check amount is valid or not for single SKU(B) in multiple(2 Unit) buy test
 
 [x] Is Discount is available or not -Check Discount Available on Selected SKU  C (Discount is  available actually)    
 
 [x] Is Discount is available or not -Check Discount Available on Selected SKU  A (Discount is  available actually)    
 
 [x] Is Discount is available or not -Check Discount Available on Selected SKU  E (Discount is not available actually) 
 
 [x] Given SKU list is Valid Or Not -We provide input of SKU and return false if SKU is not valid(Provided input AAAB) 
 **
 
 



** PART.2-src folders are as follows** Just Run the index.php file for view ,
and enter the number of product with respected SKU you will get the final amount
