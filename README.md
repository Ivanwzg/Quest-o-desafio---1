import java.util.*;public class Main
{
public static void main(String[] args)
{
Scanner scanner = new Scanner(System.in);

char letra1, letra2, letra3;

System.out.println("Insira a primeira letra.");
letra1=scanner.next().charAt(0);
System.out.println("Insira a segunda letra.");
letra2=scanner.next().charAt(0);
System.out.println("Insira a terceira letra.");
letra3=scanner.next().charAt(0);

if ((letra1 > letra2) && (letra2 > letra3)) {
System.out.println("As letras estão em ordem decrescente.");
} else {
if ((letra1 < letra2) && (letra2 < letra3)) {
System.out.println("As letras estão em ordem crescente.");
} else {
System.out.println("As letras estão desordenadas.");
}
}
}
}
