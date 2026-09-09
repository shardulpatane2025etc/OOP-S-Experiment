#include <iostream>
using namespace std;

void read(int a[], int n)
{
    cout << "Enter " << n << " elements: ";

    for(int i = 0; i < n; i++)
    {
        cin >> a[i];
    }
}

void swapNum(int &x, int &y)
{
    int temp;

    temp = x;
    x = y;
    y = temp;
}


void sort(int a[], int n)
{
    for(int i = 0; i < n - 1; i++)
    {
        for(int j = 0; j < n - i - 1; j++)
        {
            if(a[j] > a[j + 1])
            {
                swapNum(a[j], a[j + 1]);
            }
        }
    }
}
void display(int a[], int n)
{
    cout << "Sorted array: ";

    for(int i = 0; i < n; i++)
    {
        cout << a[i] << " ";
    }
}

int main()
{
    int a[50], n;

    cout << "Enter number of elements: ";
    cin >> n;

    read(a, n);
    sort(a, n);
    display(a, n);

    return 0;
}
