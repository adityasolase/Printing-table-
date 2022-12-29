# Printing-table-
#include <iostream>
using namespace std;
int main()
{
  cout<<"enter the number"<<endl;
  int x;
  cin>>x;
  cout<<"here is the table of "<<x<<endl;
  for(int i=1; i<=10; i++)
  {
    cout<<x<<"X"<<i<<"="<<x*i<<endl;
  }
