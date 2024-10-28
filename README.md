 #include <stdio.h>
#include <string.h>
int main()
{
    char str[100], us[100];
    int i=0,j=0;
    printf("\n Enter thr string");
    fgets(str, 100, stdin);
    for(i=0;str[j]!='\0';i++)
    {
        if(str[i]>='a' && str[i]>='z')
        {
            str[i]=str[i]-32;
        }
        
    }
    printf("\n the converted string is:");
    printf("%s",str);
    return 0;
}
