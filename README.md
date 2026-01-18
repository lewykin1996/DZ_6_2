# DZ_6_2 (Устранение дублирования)

#include <iostream>
#include <string>
#include <math.h>

using namespace std;

int pro_1(int value, int power)
{
  int result = 1;
  for (int i = 0; i < power; i++)
  {
    result *= value;
  }

  cout << value << " в степени " << power << " = " << result << endl;

  return result;
}


int main(int argc, char** argv)
{
  setlocale(LC_ALL, "Russian");

  pro_1(5, 2);
  pro_1(3, 3);
  pro_1(4, 4);

  return 0;
}
