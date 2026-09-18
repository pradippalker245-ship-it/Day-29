#include <stdio.h>

enum Signal
{
    RED,
    YELLOW,
    GREEN
};

int main()
{
    enum Signal s;
    int choice;

    printf("Enter signal number (0-2): ");
    scanf("%d", &choice);

    s = choice;

    switch(s)
    {
        case RED:
            printf("RED Signal\n");
            printf("STOP the vehicle\n");
            break;

        case YELLOW:
            printf("YELLOW Signal\n");
            printf("WAIT for green\n");
            break;

        case GREEN:
            printf("GREEN Signal\n");
            printf("GO the vehicle\n");
            break;

        default:
            printf("Invalid signal\n");
    }

    return 0;
}# Day-29
My c language daily practice 
