#include <iostream>
using namespace std;

class Complex
{
    int real, imag;

public:
    void get()
    {
        cout << "Enter real part: ";
        cin >> real;
        cout << "Enter imaginary part: ";
        cin >> imag;
    }

    void add(Complex c)
    {
        cout << "Addition = "
             << real + c.real << " + "
             << imag + c.imag << "i\n";
    }

    void sub(Complex c)
    {
        cout << "Subtraction = "
             << real - c.real << " + "
             << imag - c.imag << "i\n";
    }

    void multiply(Complex c)
    {
        cout << "Multiplication = "
             << real * c.real - imag * c.imag << " + "
             << real * c.imag + imag * c.real << "i\n";
    }

    void divide(Complex c)
    {
        float d = c.real * c.real + c.imag * c.imag;

        cout << "Division = "
             << (real * c.real + imag * c.imag) / d << " + "
             << (imag * c.real - real * c.imag) / d << "i\n";
    }

    void conjugate()
    {
        cout << "Conjugate = "
             << real << " - "
             << imag << "i\n";
    }
};

int main()
{
    Complex c1, c2;

    cout << "Enter first complex number:\n";
    c1.get();

    cout << "\nEnter second complex number:\n";
    c2.get();

    cout << "\n";

    c1.add(c2);
    c1.sub(c2);
    c1.multiply(c2);
    c1.divide(c2);
    c1.conjugate();

    return 0;
}
