/** Instrucciones de Control.El caso if*/
#include <ionstream>
using namespace std;
int main()
{
    // if
    //operadores relacionales: >, <, >=, <=, ==, !=
    //Mayor que
    int a, b, c;
    cout << "Ingrese tres numeros:";
    cin >> a >> b >> c;
    if (a > b)
   {
       if (a > c)
          cout << " El mayor es: " << a << endl;
       else 
          cout << " El mayor es: " << c << endl;
  }
  else
  {
      if (b > c)
         cout << "El mayor es: " << b << endl;
      else
         cout << "El mayor es: " << c << endl;
  }
  //Menor que o igual
  if (a <= b)
      cout << "a es menor o igual que b" << endl;
  else 
      cout << "a es mayor que b" << endl;
  //Igual que
  if (a == b)
      cout << "a es igual que b" << endl;
  else
      cout << "a es diferente de b" << endl;
  //Diferente de
  if (a !=b)
      cout << "a es diferente de b" << endl;
  else
      cout<< "a es igual que b" << endl;
  return θ;
 }  
