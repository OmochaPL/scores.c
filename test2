#include <stdio.h>
#include <cs50.h>

void chart(int score);

int main(void)
{
    int a = 3;
    //Get scores from user
    int scores[a];
    for (int i = 0; i <a; i++)
    {
        scores[i] = get_int("Score %i: ", i + 1);
    }
//Chart scores
    for(int i = 0; i < a; i++)
    {
        printf("Score %i: ", i + 1);
        chart(scores[i]);
    }
}
// Generate bar
void chart(int score)
{
    for(int i = 0; i < score; i++)
     {
        printf("#");
    }
    printf("\n");
}
