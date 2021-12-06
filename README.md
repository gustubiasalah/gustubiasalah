#include <stdio.h>
#include <string.h>  

int main()
{
    //Counted
    //for
    /*printf("\nContoh For 1");
    for (int i =0; i < 5; i++)
    {
        printf("\ndata ke - %d", i);
    }

    printf("\nContoh For 2");
    int j;
    for (j = 0; j < 5; j++)
    {
        printf("\ndata ke %d", j);
    }
    printf("\nContoh For Counter --");
    for (int k=5; k >= 0; k--)
    {
         printf("\ndata ke - %d", k);
    }*/

    //Uncounted
    //while
    /*printf("\nPerulangan unCounted While");
    int i= 6;
    while (i <= 5)
    {
        printf("\ndata ke %d", i);
        i ++;
    }

    //do while
    printf("\nPerulangan unCounted do While");
    int j = 6;
    do
    {

        printf("\ndata ke %d", j);
        j ++;
    } while (j <= 5);*/

    printf(".::Aplikasi 4::.");
    char nilai[]= "No";
    int index= 1;
    while (index != 0)
    {
        printf("\nApakah anda ingin keluar dari aplikasi ?");
        printf("\nKetikkan Yes atau y");
        printf("\nKetikan No");
        printf("\nPilihan :");
        scanf("%s", &nilai);

        if ((strcmp(nilai, "Yes") == 0) || (strcmp(nilai, "y") ==0))
        {
            index = 0;
        }
        else 
        {
            
            printf("\nPerulangan ke - %d", index);
            index++;
        }
    }
    printf("Terimakasih anda telah menggunakan aplikasi!");
    return 0;
}
