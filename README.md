 Demo-project
#include <stdio.h>

int main() {
    float num1, num2, num3, average;

    // Input three numbers
    printf("Enter first number: ");
    scanf("%f", &num1);
    printf("Enter second number: ");
    scanf("%f", &num2);
    printf("Enter third number: ");
    scanf("%f", &num3);

    // Calculate average
    average = (num1 + num2 + num3) / 3.0;

    // Display result
    printf("Average = %.2f\n", average);

    return 0;
}
