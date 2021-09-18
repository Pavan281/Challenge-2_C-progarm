# Challenge-2_C-progarm
# Challenge-2: Using Conditional Statements
#include <stdio.h>
int main()
{
    char Choice ;
    printf("Enter your Choice\n");
    scanf(" %c" , &Choice);
    switch(Choice)
    {
        case '1':
            printf("Food Item - Pizza\nPrice - Rs 239\n");
            break;
        case '2':
           printf("Food Item - Burger\nPrice - Rs 129\n");
           break;
        case '3':
           printf("Food Item - Pasta\nPrice - Rs 179\n");
           break;
        case '4':
           printf("Food Item - French Fries\nPrice - Rs 99\n");
           break;
        case '5':
           printf("Food Item - Sandwich\nPrice - Rs 149\n");
           break;
        default:
           printf("Invalid Choice\n");
    }
    return 0;
}
