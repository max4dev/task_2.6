# task_2.6


import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        double a = 0;
        double b = 0;
        Scanner scan = new Scanner(System.in);
        System.out.print("Введите первое число - a: ");
        a = scan.nextDouble();
        System.out.print("Введите первое число - b: ");
        b = scan.nextDouble();

        if (a%b == 0) {
            System.out.println("Делится!");
        } else {
            System.out.println("Не делится. Остаток деления - " + "%.2f", a % b);
        }
    }
}
