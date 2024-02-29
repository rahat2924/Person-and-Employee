 class Person {
 private String firstName;
 private String lastName;
 public String getFirstName() {
 return firstName;
 }
 public String getLastName() {
 return lastName;
 }
 }
 class Employee extends Person {
 private String employeeId;
 public String getEmployeeId() {
 return employeeId;
 }
 @Override
public String getLastName() {
 return super.getLastName() + ",
 Employee";
 }
 }
 public class Main {
 public static void main(String[]
 args) {
 Employee employee = new
 Employee();
 employee.getFirstName();
 employee.getLastName();
 employee.getEmployeeId();
 }
 }
