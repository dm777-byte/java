Получилась следующая конструкция:
public class Employee{
String full_name;
String position;
String phone;
String salary;
String age;
public Employee(){ // создание конструктора
System.out.println("full_name, position, phone,salary,age");
full_name = "Safonov";
position = "ingineer";
phone = "+795856291000";
salary = "five thousend";
age = "29";
}
public static void main (String[] args) {
Employee e1 = new Employee(); // вызываем конструктор класса Employee
e1.full_name = "Safonov";
e1.position = "ingineer";
e1.phone = "+795856291000";
e1.salary = "five thousend";
e1.age = "29";
System.out.println("Employee" + e1.full_name + "of postion" +e1.position + "is of phone" + e1.phone + "of salary" + e1.salary + "is of age" + e1.age);

}
}
В консоли выводится автозаполнение. Но мне не совсем ясно, почему не получается в полях там где целочисленные переменные вместо string поставить int (например не String phone или String age а int phone). На счёт конструктора, мне не понравилось то что в лекции Вы создали 3 класса, и там какая-то путаница. Более понятно, было бы если бы  объяснили всё в одном классе. Но как я понял, для того чтобы создать конструктор нужно его публично объявить и название конструктора должно совпадать с название класса. соответственно далее в майне мы должны сделать его вызов.
