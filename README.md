﻿Inicialmente falando o programa é baseado em funcionamento com potencias de dois.

Por isso é recomendado que a execução seja feita com numeros multiplos de 2

Entretanto, há uma função para evitar esse problema caso seja necessário.

Para compilar o programa: 

gcc -o external external.c -lm (-lm necessário devido ao uso da biblioteca math.h)

AVISO: APENAS VÁLIDO SE O COMPILADOR JÁ ESTIVER PRÉ INSTALADO EM SEU COMPUTADOR

Para executar o exe já presente:

./external -Numero Escolhido-

exemplo: ./external 16

AVISO: AMBOS OS COMANDOS DEVEM SER EXECUTADOS NO TERMINAL COM A SELEÇÃO DA PASTA 
DEVIDAMENTE FEITA

EXEMPLO:
PS C:\Users\Gabri\Documents\Arq_external> gcc -o external external.c -lm
PS C:\Users\Gabri\Documents\Arq_external> ./external 8 


Caso queira substituir o arquivo a ser ordenado, altere o nome do arquivo pelo desejado na linha 65 (compativel com os dados passados pela struct)
