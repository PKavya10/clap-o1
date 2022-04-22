#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    
    int billamt,amtgiven,quotient,remainder;
    scanf("%d",&amtgiven);
    scanf("%d",&billamt);
    quotient=amtgiven/billamt;
    remainder=amtgiven%billamt;
    printf("Quotient:%d\nRemainder:%d",quotient,remainder);
    
    return 0;
}
