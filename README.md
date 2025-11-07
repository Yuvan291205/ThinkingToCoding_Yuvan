# ThinkingToCoding_Yuvan

## Steps involved:

```
1.Where we are using #include<stdio.h> which includes the input,output as well as printf

2.Creates an array of strings.

3.Stores the number of steps

4.Loops through all steps using index i.

5.Prints each string 

6.Prints the final message.



```

## Code :
```
#include <stdio.h>

int main()
{
    char *sequence[] =
{
        "Boil the water",
        "Add tea powder and sugar",
        "Add milk",
        "Boil for a while",
        "Turn off the flame",
        "Strain off and serve"
    };

    int length = 6;  
    for (int i = 0; i < length; i++)
{
        printf("%s\n\n", sequence[i]);
    }

    printf("Tea is ready!!\n");

    return 0;
}

```
