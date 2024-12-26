# Shravani-Avadhut-Tarlekar
#include<stdio.h>

int main()

{

	int num;

	// using a do-while loop to repedly ask for input

	do

	{

		printf("Enter a positive number;");

		scanf("%d", &num);

		if(num <= 0)

		{

			printf("Invalid input . Please enter a positive number.\n");

		}

	} while(num<=0);// loop continuse if the input is not positive

	//positive number is enterd

	return 0;

}
