#include <stdlib.h>
#include <stdio.h>

double convertion(double euro)
{
    return 6.55957 * euro;
}

double  invConvertion(double franc)
{
    return franc / 6.55957;
}

int main(int argc, char** argv)
{
double euro = 0.0,frank = 0.0, mode = 0.0;
    printf("choisissez le mode:\n\n0 : Franc -> Euro\n1 : Euro -> Franc\n\n");
scanf("%lf",&mode);
if(mode)
{
printf("Euro...\n");
scanf("%lf", &euro);
frank=convertion(euro);
printf ("%f euro = %f franc\n\n",euro,frank);
}
else
{
    printf("Franc...\n");
scanf("%lf", &frank);
euro=invConvertion(frank);
printf ("%f franc = %f euro\n\n",frank,euro);
}
.
    return 0;

}
