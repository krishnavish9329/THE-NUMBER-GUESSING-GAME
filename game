#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main()
{
int number, guess, i; // i is count term of game
srand(time(0));
i=0;
number = rand()%100 +1;
//printf("the number is %d \n ",number); // checking the number
printf(" ///WELCOME THE NUMBER GUESSING GAME/// \n ");
do{
 printf("enter the number between 1 to 100  :");
 scanf("%d",&guess);
 if(guess>number)
 {
   printf("that number is lower number please \n");
     } 
 else if(guess<number)
 {
   printf("that number is higther number please\n");
 }
 else
 {
   printf("you guess it in %d attemts \n ",i);
 }	
  i++;
} while(guess !=number);
   return 0;
}
