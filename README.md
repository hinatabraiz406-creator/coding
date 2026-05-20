#include <iostream>
using namespace std;

int main()
{
    char op;
    float num1, num2:
    cout<<"Enter operator(+,-,*,/)";
    cin<<op;
    cout<<"Enter two number=";
    cin>>num1,num2;
    switch(op)
    {
    case'+';
      cout<<"Result:"<<num1+num2;
      break;
    case'-';
       cout<<"Result:"<<num1-num2;
       break;
      case'*';
        cout<<"Result:"<<num1*num2;
        break;
      case'/';
        if(num2!=0)
         cout<<"Result:"<<num1/num2;
        else
          cout<<"Error! Division by zero is not possible.";
          break;
      default:
        cout<<"Error! operator is not correct.";
        break;
    }
  return 0;
} 
