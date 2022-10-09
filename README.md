#include <stdio.h>
#include <stdlib.h>


/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(void)
{
int N ,m,h,s1,s2;
printf("donner N "); //a3tini la3dad li t7eb te7seb aalih
scanf("%d",&N);// stokit la3dad

h=N/3600;
m=(N%3600)/60;
s1=(N%3600);
s2=s1%60;

printf("le nombre en heure %d et en minutes est %d et en seconde %d",h,m,s2);


}

