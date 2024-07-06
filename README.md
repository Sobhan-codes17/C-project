#include<stdio.h>
#include<math.h>
int main()
{
    float f,c,v;
    printf("enter the temperature unit \n f=0/c=1:");
    scanf("%f",&v);
    printf("v=%f\n",v);
    if(v=){
    printf("enter temperature in Fahrenheit ");
    scanf("%f",&f);
    float C=(f-32)*5/9;
    printf("=%.2f°celcius\n",C);
    }
    else if(v=1){
    float F=(c*5/9)+32;
    printf("Enter temperature in Celcius: \n");
    scanf("%f",&c);
    printf("=%.2f°Fahrenheit\n",F);
    }
    else{
    printf("f");
    }
    return 0;
}
