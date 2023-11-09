#include <iostream>
#include <cstdlib>
#include <ctime>
#include <wchar.h>
#include <Windows.h>
#include <algorithm>
#include <vector>
#include <string>
#include <string.h>
#include <stdlib.h>
#include <cstring>
#include <conio.h>
#include <iomanip>
#include <process.h>



using namespace std;



int main()
{
    const char* str = "12345";
    int len = strlen(str);

    char* ptr;
    ptr = new char[len + 1];

    strcpy(ptr, str);

    cout << "ptr = " << ptr << endl;

    delete[] ptr;
    return 0;
}
