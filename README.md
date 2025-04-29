# CPP MODULE 1 :
# 1a:
# PROGRAM STATEMENT :
 Write a c++ program to display "Hello World" in to output device?
# ALGORITHM :
1. Start
2. Include Header Files: Use the necessary header file for input and output operations.
3. Define the main Function: Every C++ program requires a main function.
4. Use std::cout for Output: Use std::cout to display the desired message on the output screen.
5. Return 0: Indicate successful execution of the program.
6. End
# PROGRAM :
 ```
 Name:Dilip Kumar R
 Reg no:212222040037 
 #include <iostream>
 using namespace std;
 int main()
 {
 cout<<"Hello World"<<endl;
 }
```
# OUTPUT :
 ![image](https://github.com/user-attachments/assets/cbb1a1f8-b2e8-4721-b49e-2a8a918c84fc)
# RESULT :
Thus, The program is verified and executed successfully.The outputs match the expected 
results, confirming its correctness.

# 1b:
# PROGRAM STATEMENT :
write a program to swap two numbers using reference?
# ALGORITHM :
1. Start: Define a class with two private member variables.
2. Declare Methods: Add public methods to set numbers, swap them, and display results.
3. Define Methods Outside: Use the scope resolution operator :: to define methods for setting, 
swapping, and displaying numbers.
4. Use in Main: Create an object, call methods to set numbers, swap, and display them.
5. End: Display swapped numbers and terminate the program.
# PROGRAM :
```
#include <iostream>
using namespace std;
void swapNumbers(int &a, int &b)
{
 int temp = a;
 a = b;
 b = temp;
}
int main() 
{
 int num1, num2;
 cin >> num1;
 cin >> num2;
 swapNumbers(num1, num2);
 cout << num1 <<" "<< num2;
 return 0;
}
```
# OUTPUT :
![image](https://github.com/user-attachments/assets/d122818e-7edd-4582-9bd4-199bcf610c03)

# RESULT :
Thus, The program is verified and executed successfully.The outputs match the expected 
results, confirming its correctness.

# 1c :
# PROGRAM STATEMENT :
 Write a C++ program to display "Hello world!" using default constructor .
# ALGORITHM :
1. Define a class with a default constructor.
2. In the constructor, use std::cout to display "Hello world!".
3. Define the main function to create an object of the class.
4. The default constructor is automatically invoked when the object is created.
5. End the program after displaying the message.
# PROGRAM :
```
#include <iostream>
using namespace std;
class MyClass 
{
 public:
 MyClass() 
 {
 cout << " Hello World!"<< endl;
 }
};
int main()
{
 MyClass obj;
 
 return 0;
}
```
# OUTPUT :
 
 ![image](https://github.com/user-attachments/assets/17b73b59-8be1-4605-9bdd-3d41f945a8ff)

# RESULT :
Thus, The program is verified and executed successfully.The outputs match the expected 
results, confirming its correctness.

# 1d :
# PROGRAM STATEMENT :
Write a C++ program to convert Celsius into Fahrenheit using inline function 
# ALGORITHM :
1. Read the temperature in Celsius from the user.
2. Use the celsiusToFahrenheit() function to convert Celsius to Fahrenheit.
3. Apply the formula (Celsius×9.05.0)+32(\text{Celsius} \times \frac{9.0}{5.0}) + 32(Celsius×5.09.0
)+32 within the function.
4. Save the converted temperature in a variable named fahrenheit.
5. Display the temperature in Fahrenheit to the user.
# PROGRAM :
```
#include <iostream>
using namespace std;
inline double celsiusToFahrenheit(double celsius)
{
 return (celsius * 9.0 / 5.0) + 32;
}
int main() 
{
 double celsius;
 
 cin >> celsius;
 
 double fahrenheit = celsiusToFahrenheit(celsius);
 
 cout << "temperature in Fahrenheit:" << fahrenheit << endl;
 
 return 0;
}
```
# OUTPUT :
![image](https://github.com/user-attachments/assets/63dfb864-af9f-4451-92b3-850379c69476)

# RESULT :
Thus, The program is verified and executed successfully.The outputs match the expected 
results, confirming its correctness.
