# pythogoras-with-c
pythogoras with C

//pythagoras theorem

#include <stdio.h>
#include <math.h>

int main(){

double a;
double b;
int c;

printf(" \n side of A:");
scanf("\n %lf" ,&a);

printf(" \n side of B :");
scanf("\n %lf" , &b);

a = pow(a,2);
b = pow(b,2);
c = sqrt(a + b);

printf(" \n the side C : %d ", c);

    return 0;
}

