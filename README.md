# Motor-control-problem-
#include <stdio.h>

int main() {
    int motor;
    printf("Enter 1 to turn ON the motor or 0 to turn OFF the motor: ");
    scanf("%d", &motor);

    if (motor == 1) {
        printf("Motor is ON.\n");
    }
    else if (motor == 0) {
        printf("Motor is OFF.\n");
    }
    else {
        printf("Invalid input! Please enter 1 or 0.\n");
    }

    return 0;
}