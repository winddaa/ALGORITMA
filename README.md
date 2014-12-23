#include <stdio.h>
#include <conio.h>
main()
{
int menu;
printf ("TUGAS: KUIS ALGORITMA\n");
printf ("masukkan pilihan : \n");
printf ("1. Index 3 terletak di index ke berapa\n");
printf ("2. Urutan menggunakan seleksi minimal\n");
printf ("pilihan anda :");
scanf ("%d",&menu);
switch (menu)
case 1:{
    int  i, j, x=3, y, a[2][5]={4, 5, 8, 1, 2, 3, 11, 23, 10, 13};
    printf("Mencari index bilangan 3 pada matrix A[2][5]\n");
    for(i=0; i<2; i++){
        for(j=0; j<5; j++){
            y = a[i][j];
            if(a[i][j]==x){
                    printf("\nBilangan 3 ditemukan pada index [%d][%d]\n", i, j, a[i][j]);
                }

case 2 : {
    int i, j, l, r, min, y, a[2][5]={4, 5, 8, 1, 2, 3, 11, 23, 10, 13};
    printf("Mengurutkan matriks A[2][5] dari nilai terkecil\n");
    for(i=0; i<2; i++){
        for(j=0; j<5; j++){
            min = a[0][0];
            if(a[i][j]>min){
                    min = a[i][j];
                    l = i;
                    r = j;
                }
        printf("%d\t", min);
        }
        y = a[i][j];
        a[i][j] = min;
        a[l][r] = y;
        printf("\n", min);
    }
}
}
}
}
}
