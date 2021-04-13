**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**

*Linguagens de Programação I - 2020/2021*

# Ficha de Exercícios - 7: Ficheiros

Na resolução destes exercícios deve ser utilizada a Linguagem de Programação C. Para além da correta implementação dos requisitos, tenha em conta os seguintes aspetos:

- O código apresentado deve ser bem indentado. 
- O código deve compilar sem erros ou *warnings* utilizando o *gcc* com as seguintes flags:
- `gcc -Wall -Wextra -Wpedantic -std=c99 -g exercicio1.c -o exercicio1`
- Tenha em atenção os nomes dados das variáveis, para que sejam indicadores daquilo que as mesmas vão conter.
- Evite o uso de constantes mágicas. 
- Evite duplicação de código. 
- Considere a implementação de funções para melhorar a legibilidade, evitar a duplicação e criar soluções mais genéricas.

1. Implemente um programa que indique se podemos ou não abrir um determinado ficheiro.

2. Implemente um utilitário que permita copiar um ficheiro para outro. O utilitário deverá receber o nome dos ficheiros por argumento.
	```bash
	.\mycopy fichOrigem.txt fichDestino.txt
	```
3. Implemente um utilitário que permita calcular quantas palavras existem num ficheiro. O utilitário deverá receber o nome dos ficheiros por argumento.

4. Suponha que possui um ficheiro que contém em cada linha o nome de um aluno (apenas uma palavra) e a sua respetiva classificação (0..20).
	|Nome	| Class.|
	|-------|-------|
	|Maria	| 14	|
	|João	| 18	|
	|Zé	| 4	|
	|Rute	| 7	|
	
   Escreva um programa que:
   
   a) mostre no ecrã do seu computador apenas os alunos que obtiveram aprovação e respetivas notas (classificação >= 10) na disciplina a que o ficheiro corresponde. 

   b) calcule a media da turma, e indique o nome da pessoa que teve a melhor nota, indicando seu nome e nota.
 

5. Escreva um programa que leia um vetor com 10 inteiros a partir do teclado e guarde os seus valores no ficheiro DADOS.DAT (em binário).

6. Escreva um programa que abra o ficheiro DADOS.DAT (em binário) e apresente no ecrã a soma dos inteiros que contém.
