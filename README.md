# konversi-basis-bilangan-10-ke-bilangan-biner

    #include <iostream>
    #include <conio.h>

    using namespace std;
    void binary(int desimal )
     {
    int sisa;
    int hasil;

    if(desimal <=1)
    {
       cout<<desimal;
       return;
    }
    sisa = desimal %2;
    hasil= desimal/2;
    binary(hasil);
    cout<<sisa;

    }
    int main ()
    {
    int a;
    cout <<"masukkan bilang yang akan dikonversi = ";
    cin>>a;
    cout<<a<<"dalam biner adalah = ";
    binary(a);


    return 0;

  }
  
  
hasil
![img](https://github.com/Masdiaditia/konversi-basis-bilangan-10-ke-bilangan-biner/blob/master/konversi%20bil.biler.png?raw=true)
