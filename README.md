# WEEK2_1
โปรแกรมรายสัปดาห์ที่ 2 อันที่ 1

#include <stdio.h>
#include<math.h>


    int main(){
    double a;
    double b;
    double c;
   
    //A3 full
    printf("Enter sides of a triangle (such as :3 4 5) : ");
    scanf("%lf %lf %lf", &a ,&b ,&c);
  
    double A = ((a+b+c)*(b+c-a)*(a+c-b)*(a+b-c))/16;
    printf("%lf",sqrt(A));

    }
