# The-greatest-number
It shows you the greatest number 
#include <iostream>

using namespace std;

int main()
{
    int a;
    int b;
    int c;

    cin >> a;
    cin >> b;
    cin >> c;

    int x = ((a+b) +abs(a-b))/2;
    int y = ((x+c) +abs(x-c))/2;

    cout << y << " eh o major" << endl;

    }
    return 0;
}
