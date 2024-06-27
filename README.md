
### README for Temperature Converter

```markdown
# Temperature Converter

This is a simple temperature converter program implemented in Java. It converts temperature from Celsius to Fahrenheit.

## How to Use

1. The program will prompt you to enter the temperature in Celsius.
2. Enter the temperature in Celsius and press Enter.
3. The program will display the temperature in Fahrenheit.

## Code Example

```java
import java.util.Scanner;

public class TemperatureConverter {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.println("Enter temperature in Celsius: ");
        double celsius = scanner.nextDouble();
        
        double fahrenheit = (celsius * 9/5) + 32;
        
        System.out.println("The temperature in Fahrenheit is: " + fahrenheit);
        scanner.close();
    }
}
