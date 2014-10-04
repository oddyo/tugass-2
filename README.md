#include <stdio.h>
#include <conio.h>

main()
{
 	int pilihan,pilihan2;
   float a,b,hasil;
   do
   {
   printf("\nNama: DODY SETYO HANDOKO ");
   printf("\nNIM: 3143111044");
   printf("\nkelas : Manajemen Informatika B");
   printf("\nPROGRAM OPERASI MATEMATIKA \n");
   printf("\n1. PENJUMLAHAN");
   printf("\n2. PERKALIAN");
   printf("\n3. PENGURANGAN");
   printf("\n4. PEMBAGIAN");
   printf("\nMasukkan angka pilihan yang anda mau : ");
   scanf("%d",&pilihan);
   if	(pilihan==1)
   	{
       printf("\nPENJUMLAHAN");
       printf("\n=================");
       printf("\nMasukkan angka pertama ");
       scanf("%f",&a);
       printf("Masukkan angka kedua ");
       scanf("%f",&b);
       hasil=a+b;
       printf("\nHasil penjumlahan %3.1f + %3.1f = %3.1f",a,b,hasil);
      }
   else if(pilihan==2)
   	{
       printf("\nPERKALIAN");
       printf("\n=================");
       printf("\nMasukkan angka pertama ");
       scanf("%f",&a);
       printf("Masukkan angka kedua ");
       scanf("%f",&b);
       hasil=a*b;
       printf("\nHasil Perkalian %3.1f * %3.1f = %3.1f",a,b,hasil);
      }
   else if(pilihan==3)
   	{
       printf("\nPENGURANGAN");
       printf("\n=================");
       printf("\nMasukkan angka pertama ");
       scanf("%f",&a);
       printf("Masukkan angka kedua ");
       scanf("%f",&b);
       hasil=a-b;
       printf("\nHasil Pengurangan %3.1f - %3.1f = %3.1f",a,b,hasil);
      }
   else if(pilihan==4)
   	{
       printf("\nPEMBAGIAN");
       printf("\n=================");
       printf("\nMasukkan angka pertama ");
       scanf("%f",&a);
       printf("Masukkan angka kedua ");
       scanf("%f",&b);
       	if(b==0)
         	printf("\nTidak bisa di bagi dengan nol");
            else {
       		hasil=a/b;
       printf("\nHasil Pembagian %3.1f / %3.1f = %3.1f",a,b,hasil);
       		}
      }
   else
   	{
      printf("Tidak bisa! Coba lagi! ");
      printf("\n1. Ya");
      printf("\n2. Tidak\n");
      scanf("%d",&pilihan2);
      }
   printf("\n\nCoba lagi?");
   printf("\n1. Ya");
   printf("\n2. tidak\n");
   scanf("%d",&pilihan2);
   getch();

   }
   while(pilihan2==1);

}
