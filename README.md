# Prime-using-c-
creating prime numbers using c++
#include <iostream>
using namespace std;

void findMultiples(int n){
  for(int i = 0; i <= n; i++)
    if(i % 3 == 0 && i % 5 == 0)
      cout << i << endl;
}

int main() {
  findMultiples(120);

  return 0;
}
