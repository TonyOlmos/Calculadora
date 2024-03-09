package com.mycompany.calculadora;
import javax.swing.JOptionPane;
/**
 *
 * @author 
 */
public class calculadora {

    public static void main(String[] args) {
       int n1=Integer.parseInt(JOptionPane.showInputDialog( "Digita el número 1:" ));
       int n2=Integer.parseInt(JOptionPane.showInputDialog( "Digita el número 2:" ));

       operaciones Op=new operaciones();
       int suma=Op.sumar ( n1 , n2 );
       int resta=Op.resta ( n1 , n2 );
       int multiplicacion=Op.multiplicacion ( n1 , n2 );
       int division=Op.divison ( n1 , n2 );
       Op.mostrarResultados (suma,resta,multiplicacion,division);
    }
    }
