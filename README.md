# calculator
#WSQ03

#include <iostream>
using namespace std;
int x,y,sum, product, difference, division;
double reminder, div;
int  main()
{
cout <<"Enter first no: "; cin>>x; 
cout <<"Enter second no: "; cin>>y;

sum=x+y; cout<<"The sum is= "<< sum << endl; 
difference=x-y; cout<<"The difference is= "<< difference << endl; 
product=x*y; cout<<"The product is= "<< product << endl;
division=x/y; cout<<"The integer based division is= "<< division << endl;
reminder = x- (y*division); cout<<"The reminder is= "<< reminder << endl;
}
