# problem-1
/*
    Create a Program that Generate Multiplication mutable
    -The user is asked to enter integer to be generated
    as a multiplicaton table 
    -then the user is asked to enter the range up to which 
    multiplication table should be displayed
*/

#include <iostream>

using namespace std;

int main()
{
    int n,r;
    cout << "Enter an integer: ";
    cin >> n;
    cout << endl<< "Enter range: ";
    cin >> r;
        for(int i = 1; i <= r; ++i)
        {
            cout << endl<< n << "*" << i << "=" << n*i;
            
        }
        cout << endl<< "Programmer: EARL JHEED VALLEJOS";
    return 0;
}
