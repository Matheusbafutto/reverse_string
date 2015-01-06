#include <iostream>

using namespace std;

int main()
{  char a[50];
    int i = 0, j=0,c; 
    
   cout << "Enter String:"<< endl;
   cin >> a;
   while(a[j] != 0) {
       j += 1;
   }
   j--;
   while (i < j) {
        c = a[i];
       a[i] = a[j];
       a[j] = c;
       i++;
       j--;
   }
   cout << "The reverse string is:" << a << endl;
   
   return 0;
}

