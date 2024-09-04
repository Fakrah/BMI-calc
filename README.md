# BMI-calc
Calculate your BMI
public class BMI {
    public static void main(String[] args) {
        // Example usage
        double weight = 70.0; // Weight in kilograms
        double height = 1.75; // Height in meters
        double bmi = calculateBMI(weight, height);
        System.out.println("BMI: " + bmi);
    }

    public static double calculateBMI(double weight, double height) {
        return weight / (height * height);
    }
}
