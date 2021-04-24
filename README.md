# ProjetoFinalSistemasDistribuídos
 
## Projeto DSCalculator Idealizado Por:
- Alexandre de Moraes Furtado
- Daniel Teófilo Alves do Nascimento
- João Vitor de Araújo Braga
- Joe Álefe de Oliveira Almeida
- Vinicius de Souza Silva

## Objetivo
O Projeto Tem como Objetivo a construção de um sistema distribuído com servidores MultiThread com a função de Criar uma calculadora que aceite até dois operandos e um operador, que possa fazer as seguintes funções:

Servidor A
- Soma;			
- Subtração;		
- Multiplicação;		
- Divisão;

Servidor B
- Porcentagem;
- Raiz Quadrada;
- Potenciação.
## Sevidores e Portas
Os servidores e o cliente são carregados locamente no sistema("localhost)
As portas utilizadas foram: 5056 e 5057.
## Protocolo
O Protocolo é construído em 2 etapas, sendo elas:

-Escolha de Servidor:
 O cliente precisa escolher entre os 2 servidores disponíveis, onde 1 representa o Servidor A, e 2 o Servidor B.
 
 -Gerar Operação:
 O Cliente deve decidir fazer a entrada de dados, digitando a operação que deseja, seguindo um padrão de Operando/Operador/Operando para 2 operandos Operando/Operador para 1 operando só,Exemplo:5+5,10-2.O Cliente também as opções de enviar Exit, para sair do programa, e Voltar, para Voltar para a etapa de Escolha de Servidor;
 
 ## Como executar o projeto
Para executar o projeto, é necessário:
 - JAVA SE RUNTIME em versão 15 ou superior.
 
Para rodar no Windows, siga o seguinte passo a passo:
*  Abra o Prompt de Comando;
*  entre no caminho onde foi baixado o projeto: cd caminhodoprojeto/ArquivosJar ;
* execute o comando: java - jar ServerA.jar ;
* Abra outro Prompt de Comando;
* entre no caminho onde foi baixado o projeto: cd caminhodoprojeto/ArquivosJar ;
* execute o comando: java - jar ServerB.jar ;
* Abra outro Prompt de Comando;
* entre no caminho onde foi baixado o projeto: cd caminhodoprojeto/ArquivosJar ;
* execute o comando: java - jar Client.jar ;
- Após isso, Só executar utilizar nosso Client pelo Prompt Client.jar. 
