#include<stdio.h>
int main()
{
    //VARIABLE DECLATRATION 
    float radius; 
    float area;
    float circum;
    float diameter;

   //Taking Input from the user
    printf("Enter radius of the circle:"); 
    scanf("%f",&radius);

    area=22/7*radius*radius;

    circum=2*22/7*radius;

    diameter=radius/2;
 
    //Print Output
    printf("Area of Circle is: %f",area);
    printf("\nCircumference of Circle is: %f",circum);
    printf("\nDiameter of Circle is: %f",diameter);

    return 0;

}
