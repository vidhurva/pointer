// C++ Program that uses &amp; and * as reference and pointer operators

   #include <iostream>
   using namespace std;
   int main()
   {
           int num1, num2, hardware;
           // declaration of pointer is (data type) * (name of integer)
          int * pointer;
           pointer = &num1; // pointer is a reference to num1 using &
          *pointer = 12;    // value is assigned to memory location
           pointer = &num2;
          *pointer = 24;
  
          cout << "The value of number 1 is " << num1 << endl;
          cout << "The value of number 2 is " << num2 << endl;
          cout << "The stored memory space value of pointer is " << pointer << endl; 
          // the value of pointer becomes null
          cout << "Have a good day!" << endl;
  
  return 0;
  }
