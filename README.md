# AtividadesParadigmas
Exercícios Feitos 

Aula-1
Data: 01/09/2023 
  -Topicos 
*Paradigma Estruturado 
=>Estrutura de decisão
=>Estrutura de repetição
=>Vetorização
=>Linguagem Phyton e Java

*Paradigma Orientado a Objetos
=>Classes, Atributos e Metodos
=>Generalização(Herança)
=>Composição e Agregação
=>Transformação entre Modelos Praticas.

Exercio em aula - 01/09    Linguagem: Java

// Import das bibliotecas do scanner capturar dados do promp.
import java.util.Scanner;

//Bloco do programa Principal chamado CalculoAumentoSalarial (mesmo nome do arquivos)
public class CalculoAumentoSalarial {
    //metodo principal da classe(main) precisa ser inicializado.

    public static void main(String[] args){
        // Instaciando um objeto chamado scanner da classe abstrada Scnner
        Scanner scanner = new Scanner(System.in);

        //Bloco de Entrada de dados com o salario do funcionario.
        System.out.print("Digite so sálario do funcionario: ");

        double salario = scanner.nextDouble();
        //declaração da varialvel aumento

        double aumento;

        //Estrutura de decisão com if se o salario for maior que 1250
        if(salario > 1250.0){
            aumento = salario * 0.10;
        }else{
            aumento = salario * 0.15;
        }
        //declaração da  ova variavel com salario atualizado
        double novoSalario = salario * aumento;

        //exibição dos valores iniciais de salario antigo, novo e o aumento.
        System.out.println("O salário Antigo é de: R$ " + salario);
        System.out.println("O aumento é de: R$ " + aumento);
        System.out.println("O novo salário é: R$ " + novoSalario);

        //comando para finalizar o objeto scanner.
        scanner.close();
    }
}

⇒ Requisitos Funcionais
RFOO1 - GERENCIAR TAREFAS
RFOO2 - GERENCIAR ITENS TAREFAS
RFOO3 - MOVER TAREFAS CONCLUIDAS
======================================================================
Aula-2

PROGRAMAÇÃO ESTRUTURADA
*Algoritmos
-Formas de representação
-Descrição narrativa
-Fluxograma
-Linguagem algorítmica

*Python (práticas e exercícios)
-Implementação – Google Colab
-Jupyter Notebook
-Modularização
-->	Funções
-->	Procedures
*Programação Orientada a Objetos
-Modelagem (ADD)
-Herança
-Composição x Agregação

Algoritmo: é um conjunto de instruções pré-definidas que tem como foco resolver, de forma direcionada, determinado problema. Você terá dados de entrada, processamento e dados de saída. Há várias formas de representar um algoritmo.
A primeira forma é a descrição narrativa. Por exemplo, fazer um programa que lê 2 notas, calcula a média e verifica se o aluno foi aprovado ou reprovado.
Descrição narrativa: faça um programa que leia 2 notas e calcule sua média, e depois informe se o aluno foi aprovado ou reprovado, dado que a média tem que ser maior ou igual a 7 para ser aprovado. 
Na descrição narrativa, informamos a situação-problema que precisamos resolver.
Outra maneira de representar algoritmos é por meio de fluxograma.
Fluxograma: 
 
Linguagem algorítmica:
	INICIO
		LEIA(N1, N2)
		MED<-(N1+N2) / 2
		SE(MED >= 7) ENTÃO
			REP <- “APROVADO”
		SENÃO
			REP <- “REPROVADO”
		ESCREVA(MED)
		ESCREVA(REP)
	FIM
 
Compilador:
N1	N2	MED	REP
0.8	4.8	2.8	“Reprovado”
5.0	9.0	7.0	“Aprovado”

