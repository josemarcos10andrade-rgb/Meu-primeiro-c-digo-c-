#include <iostream>
#include <string>

using namespace std;

int main() {
    string name;
    cout << "olá" << endl;
    cout << "estou a aprender c++" << "\n";
    cout << "digite seu nome para agradecimento!" << "\n";
    cin >> name;

    if (name == "josé") {
        cout << "obrigado por testar meu chará!!!" << "\n";
    }
    else {
        cout << "obrigado por testar" << endl;
        cout << name << "\n";
    }

    return 0;
}
