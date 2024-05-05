# Repositoryprobably
#include <iostream>
#include <string>

using namespace std;
int main()
{
    setlocale(LC_ALL, "RUS");
    cout << "*СОЗДАНИЕ АККАУНТА*" << endl;
    cout << "Введите своё имя: ";
    string a;
    getline(cin, a);
    cout << "Введите свою фамилию: ";
    string b;
    getline(cin, b);
    cout << "Введите своё пароль: ";
    string password;
    getline(cin, password);
    cout << "*АККАУНТ СОЗДАН*" << endl;
    return 0;
}
