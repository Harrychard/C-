#include <iostream>
using namespace std;
int main(){
    int hari; // tpyo 'hri' diubah menjadi 'hari'
    cout << "Masukan hari keberapa [1/2/3/4/5/6/7] - "; cin >> hari;
    switch (hari){ // typo'her' diubah menjadi 'hari'
        case 1 :
            cout << "Senin" << endl;
            break; // di akhiri'break' di setiap case
        case 2 :
            cout << "Selasa" << endl;
            break;
        case 3 :
            cout << "Rabu" << endl;
            break;
        case 4 :
            cout << "Kamis" << endl;
            break;
        case 5 :
            cout << "Jumat" << endl;
            break;
        case 6 :
            cout << "Sabtu" << endl;
            break;
        case 7 :
            cout << "Minggu" << endl;
            break;
        default :
            cout << "Hari tidak ada";
    }
    return 0;}// penutup di main
