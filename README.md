# day-2-ques-2-area-and-circumference-of-circle
#include<stdio.h>
int main(){
    float rad, area, circumference;
    printf("enter the radius : ");
    scanf("%f",&rad);
    area=3.14*rad*rad;
    circumference=2*3.14*rad;
    printf("area of circle is %f\n", area);
    printf("circumference of circle is %f\n", circumference);
    return 0;
}
