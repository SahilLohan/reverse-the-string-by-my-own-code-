# reverse-the-string-by-my-own-code-


#include <stdio.h> 
#include <stdlib.h> 
#include <string.h>

int main()
{ 
    char fi[20]="hello"; 
    char sec[20];
    int i,j=0,k;
    // saving the reversed string in other array 
    for(i=strlen(fi)-1;i>=0&&j<strlen(fi);i--&&j++)
    sec[j]=fi[i];
    
    puts(sec);
    
return 0;
}


output will be :- 

olleh
