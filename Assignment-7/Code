#include <iostream>
#include <cstring>
using namespace std;

class String
{
    char str[100];

public:
    
    String()
    {
        str[0] = '\0';
    }

    
    void Accept()
    {
        cout << "Enter string: ";
        cin.getline(str, 100);
    }

    void Display()
    {
        cout << "String is: " << str << endl;
    }

    // Destructor
    ~String()
    {
        cout << "Destructor called" << endl;
    }
};

int main()
{
    String s;

    s.Accept();
    s.Display();

    return 0;
}
