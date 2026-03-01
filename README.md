# equa-o-do-segundo-grau
faculdade
 include <stdio.h>
 int main (){
  float a, b , c , delta, x1, x2

  printf( "digite os valores de a, b e c");
  scanf ("%f %f %f", &a, &b, &c);

  delta= b*b -4*a*c;
   if (delta<0){
    printf(" nao existe valores reais para delta\n");
  } else if (delta==0) { 
   x1= -b/ (2*a);
   printf(" raiz unica: %f\n", x1);
   } else {
     x1= (-b + sqrt(delta)) / (2*a);
     x2= (-b - sqrt(delta)) / (2*a);
     printf ("raizes: %f e %f\n", x1, x2);
     } 
     return0;
