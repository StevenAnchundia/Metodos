public class SalarioSemanal {

    public static double calcularSalario(double pagoHora, int horasTrabajadas) {
        double salario = pagoHora * horasTrabajadas;
        return salario;
    }

    public static void main(String[] args) {

        double pagoHora = 2.5;
        int horasTrabajadas = 40;
        
        double resultado = calcularSalario(pagoHora, horasTrabajadas);
        System.out.println("El salario semanal es: $" + resultado);
    }
}
