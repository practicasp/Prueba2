# Prueba2
Hola  yo soy  isfegama y este es  nuestro primer ensayo de nuestro proyecto de robotica.
-_-

// trataremos de hacer una calculadora

import javax.swing.JOptionPane;

public class  Suma
{

public static void main(String args[] )
{

String a = JOptionPane.showInputDialog("Escriba el primer numero: ");

int a1 = Integer.parseInt(a);

String b = JOptionPane.showInputDialog("Escriba el segundo numero: ");

int b1 = Integer.parseInt(b);

String c =  String.format( "La suma: %d + %d = %d" , a1, b1, (a1 + b1));

JOptionPane.showMessageDialog( null, c );

}}
