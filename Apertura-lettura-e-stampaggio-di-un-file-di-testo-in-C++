#include <iostream>
#include <string>
#include <fstream>// per poter usare ifstream

using namespace std;

int main()
{
    string s;//dichiarazione della stringa
    ifstream f ("readme.txt", ios::in);//apertura del file in lettura
    if (!f) cout << "Il file non esiste!";
    //f >> s; cosi inserisce nella stringa solo i caratteri della prima riga e si ferma al primo spazio
    while (f.good())// f.good "finchè ci sono caratteri"stampa: con il ciclo while stampa tutto sulla stessa riga.
        {
            getline(f,s);
            cout << s <<endl;//senza la "endl" stampa tutto sulla stessa riga. Con stampa come si trovano all'interno del file di testo
        }
    f.close();// chiusera del file
    return 0;
}
