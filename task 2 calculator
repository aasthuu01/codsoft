#include <iostream>
using namespace std;

int main() {
    double num1, num2;
    char operation;

    cout << "---Welcome to the Simple Calculator---" << endl;

    // Input numbers
    cout << "Enter first number: ";
    cin >> num1;

    cout << "Enter second number: ";
    cin >> num2;

    // Input operation
    cout << "Enter operation (+, -, *, /): ";
    cin >> operation;

    if (operation == '+') {
        cout << "Result: " << num1 + num2 << endl;
    } else if (operation == '-') {
        cout << "Result: " << num1 - num2 << endl;
    } else if (operation == '*') {
        cout << "Result: " << num1 * num2 << endl;
    } else if (operation == '/') {
        if (num2 != 0)
            cout << "Result: " << num1 / num2 << endl;
        else
            cout << "Error: Division by zero!" << endl;
    } else {
        cout << "Invalid operation!" << endl;
    }

    return 0;
}
