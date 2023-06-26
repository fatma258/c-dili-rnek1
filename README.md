
//klavyeden girilen metin uzunluğunu bulan program
#include <stdio.h>
int main(){
char metin[100];
int adet=0;
printf("metin girin");
gets(metin);
int i;
for(i=0;metin[i]!='\0';i++)
{
adet++;
}
int boyut=strlen(metin);

printf("for ile metin boyutu:%d",adet);
	
printf("strlen ile mmetin boyutu: %d",boyut);


return 0;
}
