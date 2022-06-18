//# Me-ajuda-Triangulo
//Eu estou tentando criar um código capaz de saber considerando os tamanhos dos lados definem qual tipo de triângulo.

#include <stdio.h>
int main ()
{
	int T1, T2, T3, triangulo, a, b, c;
	a = 1;
	b = 1+1;
	c = 1+1+1; 	
	printf("Digite o tamanho do primeiro lado, lembre-se que o valor da soma de dois lados nao pode ser menor que o tamanho de apenas um lado: ");
	scanf("%d", &T1);	
	
	printf("Digite o tamanho do segundo lado: ");
	scanf("%d", &T2);
	
	printf("Digite o tamanho do terceiro lado: ");
	scanf("%d", &T3);
	
	printf("1 = Equilatero; 2 = Isosceles; 3 = Escaleno"); 
	
	printf(" | ");
	
	if (T1 == T2 == T3)
	{
		
		triangulo = a;
		   
	} 
	
    else if (T1 == T2 != T3) 
	{
		
	 triangulo = b;
	   
	}
	else if(T1 != T2 == T3)
	{
		
		triangulo = b;
		
	}	 
	
	else if (T1 != T2 != T3)
	{
		
		triangulo = c;
		
	}	
		
		printf("Seu triangulo eh: %d", triangulo);
}
