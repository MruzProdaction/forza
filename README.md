#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");
    for (int num = 300; num <= 600; num++) {
        int sumforza = 0;

     for (int i = 2; i <= num / 2; i++) {
       
         if (num % i == 0) {
                sumforza += i;
         }
     }
         if (sumforza % 10 == 0) {
            cout << "Число " << num << endl;
         }
    }

    return 0;
}
