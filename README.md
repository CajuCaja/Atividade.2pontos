# Atividade.2pontos
Atividade em sala.



 /*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.testes;

import java.util.Scanner;

/**
 *
 * @author LabInfo
 */
public class igualdade {
    public static void main(String []args) {
        Scanner tela = new Scanner(System.in);
        int A = 2;
        int B = 3;
        
        if (A == B){
            System.out.println("São iguais: ");
        }else {
        
            System.out.println("São diferentes: ");
      
        }
    }
    
}
 /*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.testes;

import java.util.Scanner;

public class Desafio1 {
    public static void main(String []args) {
        Scanner tela = new Scanner(System.in);
        
        System.out.println("Primeiro número: ");
        double num1 = tela.nextDouble();
        
        System.out.println("Segundo número: ");
        double num2 = tela.nextDouble();
        
        double resultado = num1 - num2;
       
        System.out.println("Subtração de " + num1 + " por " + num2 + "é igual a: " + resultado);
    }
}



/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package demo;

/**
 *
 * @author LabInfo
 */
import java.util.Scanner;

public class demo {
    public static void main(String[] args){
        Scanner tela = new Scanner(System.in);
        
        System.out.println("Digite seu nome: ");
        String nome = tela.nextLine();
        
        System.out.println("Digite sua idade: ");
        int idade = tela.nextInt();
        
        System.out.println("Digite seu gênero (M/F): ");
        char genero = tela.next().charAt(0);
        
        System.out.println("Nome:" + nome);
        System.out.println("Idade:" + idade);
        System.out.println("Genero:" + genero);
        
       
        
                
    }
    
}


/* 
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/ClientSide/reactjs.jsx to edit this template
 */
var Hello = React.createClass({
    render: function () {
        return (
                <div></div>
                );
    }

});



/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.testes;

import java.util.Scanner;

public class Igualdade {
    public static void main(String []args) {
        Scanner tela = new Scanner(System.in);
        int A = 2;
        int B = 3;
        
        if (A == B){
            System.out.println("São iguais: ");
        }else {
            System.out.println("São diferentes! ");
      
        }
    }
    
}



package com.mycompany.exemplo0210;

/*
package program.aula; (Nome do pacote deve coincidir com o nomeado no NetBeans)
 */
import java.util.Scanner;

public class CondicaoAninhada {
 public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    // Solicitar o primeiro número ao usuário
    System.out.print("Digite o primeiro número: ");
    int numero1 = scanner.nextInt();
    // Solicitar o segundo número ao usuário
    System.out.print("Digite o segundo número: ");
    int numero2 = scanner.nextInt();
    // Comparar os números e exibir o resultado
    if (numero1 > numero2) {
        System.out.println("O primeiro número (" + numero1 + ") é maior que o segundo número (" + numero2 + ").");
    } else if (numero1 < numero2) {
        System.out.println("O primeiro número (" + numero1 + ") é menor que o segundo número (" + numero2 + ").");
    } else {
        System.out.println("Os dois números são iguais.");
    }
    // Fechar o scanner
    scanner.close();
    }
   }
