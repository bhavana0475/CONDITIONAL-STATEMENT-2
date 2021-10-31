# CONDITIONAL-STATEMENT-2
#include<stdio.h>
main()
{
	printf("\n1.Biryani,Rs 260\n2.Pastry,Rs 70\n3.Pizza,Rs 300\n4.Burger,Rs 130\n5.Pasta,Rs 220");
	int choice = 0;
	scanf("%d", &choice);
	
	switch(choice)
	{
		case 1:
			printf("Food item - Biryani");
			printf("\nPrice - Rs 260");
			break;
		case 2:
			printf("Food item - Pastry");
			printf("\nPrice - Rs 70");
			break;
		case 3:
			printf("Food item - Pizza");
			printf("\nPrice - Rs 300");
			break;
		case 4:
			printf("Food item - Burger");
			printf("\nPrice - Rs 130");
			break;
		case 5:
			printf("Food item - Pasta");
			printf("\nPrice - Rs 220");
			break;
		default :
			printf("Invalid information");
			break;
	}
	return 0;
}
