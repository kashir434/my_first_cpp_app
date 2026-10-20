#include <iostream>
using namespace std;

int main() {
    int choice;
    cout << "--- Peshawar Food App ---" << endl;
    cout << "1. Biryani - 300 Rs" << endl;
    cout << "2. Chapli Kabab - 500 Rs" << endl;
    cout << "3. Karahi - 800 Rs" << endl;
    cout << "Apna order select karo (1-3): ";
    cin >> choice;

    if(choice==1) cout << "Biryani Ordered! Shukriya!" << endl;
    else if(choice==2) cout << "Chapli Kabab Ordered!" << endl;
    else if(choice==3) cout << "Karahi Ordered!" << endl;
    else cout << "Ghalat choice!" << endl;

    return 0;
}