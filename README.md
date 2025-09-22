#include <iostream>
using namespace std;

int main() {
    int a, b;

    cout << "Enter two numbers: ";
    cin >> a >> b;

    cout << "\nBefore swapping: a = " << a << ", b = " << b << endl;

    // Swapping without a temp variable
    a = a + b;
    b = a - b;
    a = a - b;

    cout << "After swapping (without temp): a = " << a << ", b = " << b << endl;

    return 0;
}
