

#include<stdio.h>
int main()
{
    int num;
    float num2;
    double num3;
    char name;

    printf("Enter intiger number: ");
    scanf("%d",&num);
    printf("Enter float number: ");
    scanf("%f",&num2);
    printf("Enter double number: ");
    scanf("%lf",&num3);
    printf("Enter your character : ");
    scanf(" %c",&name);

    printf("Integer number: %d\n",num);
    printf("float number: %f\n",num2);
    printf("double number: %1f\n",num3);
    printf("character number: %c\n",name);


}
