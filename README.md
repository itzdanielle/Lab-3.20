# Lab-3.20
#include <iostream>
#include <iomanip>
using namespace std;

int main()
{
	double americanColonel = 85.00;		 
	double modern = 57.50;	
	double frenchClassical = 127.75;	
  double allChairs = 3021.25;
	cout << setprecision(2) << fixed;	
	
	cout << "Please input the number of American Colonel chairs sold\n";
	cin >> americanColonel;
   
	cout << "Please input the number of Modern chairs sold\n"; 
  cin >> modern; 
  
  cout << "Please input the number of French Classical chairs sold\n";
  cin >> frenchClassical; 
  
  americanColonel = 85.00 * 20;
	cout << "The total sales of American Colonel is $" << americanColonel << endl;
  modern = 15 * 57.50;
  cout << "The total sales of Modern chairs is $" << modern << endl;
  frenchClassical = 5 * 127.50;
  cout << "The total sales of French Classical chairs is $" << frenchClassical << endl;
  cout << "The total sales of all the chairs is $" << allChairs << endl;

}
