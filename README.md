# Ahmad-Ustad
#include <iostream>
using namespace std;

int main() {
    char s;
    do {
        int num;
        cout << "Enter a number: ";
        cin >> num;

        if (num % 2 == 0) {
            cout << num << " is Even." << endl;
        } 
		else {
            cout << num << " is Odd." << endl;
             }
             <h1>Ayesha-Ahmad<h1>
	     <br>
      Ahsan Ijaz

        cout << "Do you want check again ? (y/n): ";
        cin >> s;
    } while (s == 'y' || s == 'Y');
    
    cout << "Exiting program. Goodbye!" << endl;
    return 0;
}
