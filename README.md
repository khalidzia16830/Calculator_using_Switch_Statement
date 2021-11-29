# Calculator_using_Switch_Statement
KHALID ZIA "+92 317-5780828"

/*  Khalid zia
    malikawan16830@gmail.come
    +92 31757-80828
     */
# include <iostream>
using namespace std;
int main()
{
    // delaration of variable that are used as a function of calculator
    int a,b;
    // The declaration of variable who are undre switch conditions
    int choice;
    // Declaration of calculator functions
    int Addition, Subtraction, Division, Multiplication, Modulus;
    // Enter the first value for calculating
    cout << "Enter First number: ";
    cin  >>a;
    // Enter the second value for calculating
    cout << "Enter second number: ";
    cin  >>b;
    // Functions of calculators
    // sum is used for taking  addition of a and b
    Addition=a+b;
    // sub is used for taking subtraction of a and b
    Subtraction=a-b;
    // Div is used for taking division of a and b
    Division=a/b;
    // mul is used for taking  multiplication of a and b
    Multiplication=a*b;
    // mod is used for taking modulus of a and b
    Modulus=a%b;
    // The menu for choice to pick one of them
    cout << "What you want to do: "
         << "\n\tMenu"
         << "\n1. Addition "
         << "\n2. subtraction "
         << "\n3. Division "
         << "\n4. Multiplication "
         << "\n5. Modulus \n";
    cout << "\nPick-up your choice and proceeding: ";
    
    cin  >> choice;
    // switch case for the case you pick-up from the menue choice
    switch(choice){   
    // case 1 ia bout to do addition of two variables
      case 1:
      {
           cout << "You Pick-up Addition\n";
           cout << "The Addition of "<<a<<" and "<<b<<" is: "<<Addition<<endl;
    // break statement is used to break that case after executing       
                break;
          } // End of case 1
     // case 2 is bout to do subtraction of two variables      
      case 2:
      {
           cout << "You Pick-up Subtraction\n";
           cout << "The Subtraction of "<<a<<" and "<<b<<" is: "<<Subtraction<<endl;
    // break statement is used to break that case after executing 
               break;
          } // End case 2
     // case 3 is bout to do multiplictaion of two variables      
      case 3:
      {
           cout << "You Pick-up Division\n";
           cout << "The Division of "<<a<<" and "<<b<< " is: "<<Division<<endl;
    // break statement is used to break that case after executing 
              break;
          } // End case 3 
        case 4:
      {
           cout << "You Pick-up Multiplication\n";
           cout << "The Multiplication of "<<a<<" and "<<b<< " is: "<<Multiplication<<endl;
    // break statement is used to break that case after executing 
              break;
          } // End case 4
        case 5:
      {
           cout << "You Pick-up modulus\n";
           cout << "The Modulus of "<<a<<" and "<<b<< " is: "<<Modulus<<endl;
    // break statement is used to break that case after executing 
              break;
          } // End case 3        
    // default case is optional but it works when no option match your pick-up than default works      
        default :
        cout << "Your pickup choice is not right ";
    } // Ends of switch condition
        
    /* Return is doing as awork when your program ends then it return you as a integer because you say like 
    that in line no 3 with main function i.e " 'int' main() "     */
        return 0;
} // Ends main function

/* Note: '\n' is used to come in next line
          endl ('el') is also used for going in next in line
          '\t' is used fro tab, I mean insert '4' spaces at-a-time*/
