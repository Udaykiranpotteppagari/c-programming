#include <stdio.h>
#include <string.h>

union DT{ // DT is the 
    int i;
    float f;
    char str[20];
};

int main ()
{
    union DT data;
    data.i=10;
    printf("data.i %d\n",data.i);

    data.f=358934.8345;
    printf("data.f %.2f\n",data.f);

    strcpy(data.str, "Hello Union");
    printf("data.str %s\n",data.str);
    

    //Printing all the data types
    printf("data.i %d\n",data.i);
    printf("data.f %.2f\n",data.f);
    printf("data.str %s\n",data.str);
}
