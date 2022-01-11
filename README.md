#include<stdio.h>
// int main(){ 
// //Question 1. Write  program to print the address of a variable use this address to get the value of this variable
// int i=3;
//     int *j;
//     j = &i;
    
//     printf("Address of i = %u\n",&i);
//     printf("Address of i = %u\n",j);
//     printf("Address of j = %u\n",&j);
//     printf("Value i = %d \n",i);
//     printf("Value i = %d \n",*(&i));
//     printf("Value i = %d \n",*j);

// return 0;
// }

void address(int i);
int main()
{
    int i = 3;

    printf("Address of i = %u\n",&i);
    address(i);
    return 0;
}
void address(int i)
{
    printf("Address of i pass in function = %u",&i);

}
