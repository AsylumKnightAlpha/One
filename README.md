/
// Demonstration of Classes - Friend Functions
// -- initial design: Basics of Class (addition)
// Header Files
#include <iostream>

using namespace std;

// CLASS OBJECTS
/*class Mathbase
{
	private: //Acessors
		float n1;
		float n2;
	
	public: //Accessors
		//Class Functions
			//Constructor Function
			Mathbase()
			{
				n1 = 0;
				n2 = 0;
			}
			
			//Ordinary Functions
			
		
	
};*/

// FUNCTION DECLARATION
int main()
{
	//INIITALIZATION
		//Datatype Initialization - Primative datatype
		float num1, num2;
		float sum;
		//Class Initialization 
	//PROMPT USER
	cout <<"1 of 2 - Enter FIRST numeric value: ";
	cin >> num1;
	cout <<"2 of 2 - Enter SECOND numeric value: ";
	cin >> num2;
	
	//COMPUTERIZED CALCULATIONS
	sum = num1 + num2;
	//DISPLAY
	system("cls");
	cout << "First Value: " << num1 << "\n";
	cout << "Second Value: " << num2 << "\n\n";
	
	cout << num1 << " + " << num2 << " = " << sum;
	//TERMINATION

}



// FUNCTION DEFINITION

