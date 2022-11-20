#Пример #Metanit #Наследование 
[[2022-07-10]]
```java
public class Program{

 public static void main(String[] args) {

 Person tom = new Person("Tom");

 tom.display();

 Person sam = new Employee("Sam", "Oracle");

 sam.display();

 }

}

class Person {

 String name;

 public String getName() { return name; }

 public Person(String name){

 this.name=name;

 }

 public void display(){

 System.out.printf("Person %s \n", name);

 }

}

class Employee extends Person{

 String company;

 public Employee(String name, String company) {

 super(name);

 this.company = company;

 }

 @Override

 public void display(){

 System.out.printf("Employee %s works in %s \n", super.getName(), company);

 }

}
```
Консольный вывод данной программы:

Person Tom
Employee Sam works in Oracle

https://metanit.com/java/tutorial/3.5.php