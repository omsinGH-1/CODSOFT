# CODSOFT
#include<iostream>
#include<cmath> // for fmod
using namespace std;
int main()
{
 float num1,num2;
 cout<<"Enter 1st number: ";
 cin>>num1;
 cout<<"Enter 2nd number: ";
 cin>>num2;
 char op;
 cout<<"Enter arithmetic op's(+,-,/,*,%): ";
 cin>>op;
 switch(op)
    {
      case'+':
      cout<<"Result: "<<num1+num2<<endl;
      break;
      case'-':
      cout<<"Result: "<<num1-num2<<endl;
      break;
      case'*':
      cout<<"Result: "<<num1*num2<<endl;
      break;
      case'/':
      if(num2!=0)
      cout<<"Result: "<<num1/num2<<endl;
      else
      cout<<"Retake Input"<<endl;
      break;
      case'%':
      cout<<"Result: "<<fmod(num1,num2)<<endl; // fmod is for modulus operator, at float type % is not allowed
      break;
      default:
      cout<<"Invalid operation taken by user"<<endl;
    }
    return 0;
 }
