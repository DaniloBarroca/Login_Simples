# Login_Simples
//Um módulo de login, bem simples, em linguagem C

#include <stdio.h>

int main()
{
char senha = '?';

printf ("Digite sua senha!");
scanf ("%c", &senha);

if (senha == '?') {
 printf ("Voce esta logado no sistema!");
   
}else
        printf("Senha incorreta!");



return 0;
}


