# IT112-Saraus-Kent
Laboratory Exercise 3
#include <stdio.h>

int main() {

    char fullname[50];
    char section[50];
    float number1;
    float number2;

    printf("Enter your full name: ");
    fgets(fullname, sizeof(fullname), stdin);

    printf("Enter your section: ");
    fgets(section, sizeof(section), stdin);

    printf("Enter a 1st number: \n");
    scanf("%f", &number1);

    printf("Enter a 2nd number: \n");
    scanf("%f", &number2);

    float sum = number1 + number2;
    float difference = number1 - number2;
    float product = number1 * number2;
    float quotient = number1 / number2;

    printf("Student Calculator\n");
    printf("Student Name: %s\n", fullname);
    printf("Section: %s\n", section);

    printf("Results:\n");

    printf("The sum of %f and %f is %f\n", number1, number2, sum);
    printf("The difference of %f and %f is %f\n", number1, number2, difference);
    printf("The product of %f and %f is %f\n", number1, number2, product);
    printf("The quotient of %f and %f is %f\n", number1, number2, quotient);

   return 0;
}
