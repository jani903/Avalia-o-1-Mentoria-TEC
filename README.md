import java.util.Scanner;

public class Atividade1 {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);

// Pedindo as notas
System.out.println("Digite as 8 notas (uma por vez e pressione Enter):");
double n1 = sc.nextDouble();
double n2 = sc.nextDouble();
double n3 = sc.nextDouble();
double n4 = sc.nextDouble();
double n5 = sc.nextDouble();
double n6 = sc.nextDouble();
double n7 = sc.nextDouble();
double n8 = sc.nextDouble();

// Calculando bimestres
double b1 = (n1 + n2) / 2.0;
double b2 = (n3 + n4) / 2.0;
double b3 = (n5 + n6) / 2.0;
double b4 = (n7 + n8) / 2.0;

// Calculando semestres
double sem1 = (b1 + b2) / 2.0;
double sem2 = (b3 + b4) / 2.0;

// M茅dia final
double mediaFinal = (sem1 + sem2) / 2.0;

// Sa铆da formatada
System.out.println();
System.out.
