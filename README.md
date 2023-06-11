# string-funtion
some of the function of string library


#include<stdio.h>
#include<string.h>

int main(){
char name[40]= "vivek bhandari";
int l= strlen(name);
printf("the length of this string is %d \n",l);



char fn[100]="bhandari";
char sn[]="vivek";
strcpy(sn,fn);
puts(sn);


char f1[100]="vivek ";
char s1[]="bhandari";
strcat(f1,s1);
puts(f1);

char v1[10]="viveka";
char v2[10]="vivekb";
printf("string comparision = %d",strcmp(v1,v2));


return 0;

}
