# AtividadesParadigmas
Exercícios Feitos 

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
