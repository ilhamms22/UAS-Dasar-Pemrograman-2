# Ujian Akhir Semester 
<br>Mata Kuliah : Dasar Pemrograman
<br> Nama	: Ilham Marwan Sidik
<br>NIM		: 1227050055
<br>Jurusan	: [Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum

## Source Code
#include <iostream>
#include <iomanip>
using namespace std;
int main(){
    
	int arr[100][100], jumlahBaris, jumlahKolom, i, j, baris, kolom;

    cout<<" Input jumlah baris: "; 
	cin>>jumlahBaris;
    cout<<" Input jumlah kolom: "; 
	cin>>jumlahKolom;
    cout << endl;

    for(i = 0; i < jumlahBaris; i++){
        for(j = 0; j < jumlahKolom; j++){
            cout << " Baris " <<i+1<<", Kolom "<<j+1<< " = ";
            cin >> arr[i][j];
        }
        cout << endl;
    }

    cout << " Hasil input nilai : " << endl;

    for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
        cout << setw(3) << arr[i][j] << " ";
    }
    cout << endl;
    }

    cout << " Hasil bilangan yang habis dibagi 3,5,7 : " << endl;

    for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
        if(arr[i][j] % 3 == 0 || arr[i][j] % 5 == 0 || arr[i][j] % 7 == 0){
        cout << setw(3) << arr[i][j] << " ";
        }
    }
    cout << endl;
    }
	cout << endl;
}

## Output
![image](https://user-images.githubusercontent.com/121008252/208377766-5be6b7da-d6c5-4a30-99bb-608306ca6ca8.png)
