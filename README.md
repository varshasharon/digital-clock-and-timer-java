# digital-clock-and-timer-java

```
import java.time.LocalDateTime;
import java.time.format.DateTimeFormatter;
import java.util.Scanner;
import java.util.concurrent.TimeUnit;

public class Codechef {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        while (true) {
            System.out.print("Choose an option (1:Digital Clock, 2:Countdown Timer): ");
            String choice = scanner.nextLine().trim();
            userChoice(choice, scanner);
        }
    }

    public static void userChoice(String choice, Scanner scanner) {
        if (choice.equals("1")) {
            digitalClock();
        } else if (choice.equals("2")) {
            System.out.print("Enter the number of seconds to countdown: ");
            int seconds = scanner.nextInt();
            scanner.nextLine(); // Consume the newline
            countdownTimer(seconds);
        } else {
            System.out.println("Invalid choice!");
        }
    }

    public static void digitalClock() {
        // update the function 
    }

    public static void countdownTimer(int seconds) {
        System.out.println("Counting down from " + seconds + " seconds.");
    }
}


```
