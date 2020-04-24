# running-home-point
Ran ex code material . easil developed by AB

import java.util.Scanner;
import java.io.File;
import java.io.IOException;
public class DoPayroll {
    public static void main(String args[])
                                  throws IOException {
        Scanner diskScanner =
            new Scanner(new File("EmployeeInfo.txt"));
        for (int empNum = 1; empNum <= 3; empNum++) {
            payOneEmployee(diskScanner);
        }
        diskScanner.close();
    }
    static void payOneEmployee(Scanner aScanner) {
        Employee anEmployee = new Employee();
        anEmployee.setName(aScanner.nextLine());
        anEmployee.setJobTitle(aScanner.nextLine());
        anEmployee.cutCheck(aScanner.nextDouble());
        aScanner.nextLine();
    }
}





element.style {



}
body.main-page {
    background: #f7f7f7;
}
body {
    font-family: Open Sans;
}
html, body {
    padding: 0;
    margin: 0;
    width: 100%;
    height: 100%;
}
user agent stylesheet
body {
    display: block;
    margin: 8px;
}
