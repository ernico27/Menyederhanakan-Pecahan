# Menyederhanakan-Pecahan

    #include<stdio.h>
    int pecahan ();
    int main()
    {
    pecahan();
    }
    int pecahan()
    {
    int a,b,l,t;
    printf("\t\t ================================ \n");
    printf("\t\t Program menyederhanakan pecahan \n");
    printf("\t\t ================================ \n");
    printf("\t\t Masukkan pembilang : ");
    scanf("%d",&a);
    printf("\t\t Masukkan penyebut : ");
    scanf("%d",&b);
    t=a/b;
    l=a%b;
    if(a%b==0)
        printf("\t\t Bilangan (%d/%d) \n disederhanakan menjadi %d",a,b,t);
    else if(a%b!=0)
        printf("\t\t Bilangan (%d/%d) \n disederhanakan menjadi (%d %d/%d",a,b,t,l,b);
    }

## Hasilnya

![img](https://github.com/ernico27/Menyederhanakan-Pecahan/blob/master/menyederhanakan.png?raw=true)
