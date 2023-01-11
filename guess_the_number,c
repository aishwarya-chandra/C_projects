#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
{
    int num;
    srand(time(0));
    num = rand() % 100 + 1; // Generates a random number between 1 and 100
    printf("Hi! \nA random number has been generated between 1 to 100. \n");
    printf("Only 100 guesses could be done. \nCan you guess the number? \n");
    int guess = 0;
    for (int i = 1; i <= 100; i++)
    {
        scanf("%d", &guess);
        if (guess > num)
            printf("Think of a lower number \n");
        else if (guess < num)
            printf("Think of a higher number \n");
        else
        {
            printf("You guessed the correct number in %d guesses!", i);
            break;
        }
    }
    return 0;
}
