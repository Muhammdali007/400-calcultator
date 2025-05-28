import java.time.LocalDate;
import java.time.DayOfWeek;

public class FourHundredYearCalendar {
    public static void main(String[] args) {
        int startYear = 2023; // Starting year
        int yearsToGenerate = 400; // Number of years to generate

        for (int year = startYear; year < startYear + yearsToGenerate; year++) {
            for (int month = 1; month <= 12; month++) {
                LocalDate date = LocalDate.of(year, month, 1);
                System.out.println("Year: " + year + ", Month: " + month + ", First Day: " + date.getDayOfWeek());
            }
        }
    }
}
```
