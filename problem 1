#include<stdio.h>
#include<math.h>
int main()
{
    /*here lmd means lemda which is the wavelength
        and tht means theta which is the angle*/
    double lmd,tht,d,m;
    printf("Enter wavelength : ");
    scanf("%lf",&lmd);
    lmd*= 1e-9;
    if(lmd<380e-9||lmd>750e-9)
    {

       printf("Out of the range . Please enter a valid number. \n ");
    }
    else {

        printf("Enter angle : ");
        scanf("%lf",&tht);
        printf("Enter slit separation : ");
        scanf("%lf",&d);
        d*= 1e-6 ;
        m = (d*sin(tht * M_PI / 180))/ lmd;
        m = round(m);
        printf("%d-th order maxima ", (int)m);

    }

    return 0;
}
