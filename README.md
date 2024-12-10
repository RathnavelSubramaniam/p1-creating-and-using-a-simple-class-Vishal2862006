class Person
{
    string firstName;
    string lastName;
    int age;
//Default constructor
  public person()
{
    firstName = "";
    lastName = "";
    age = 0;
}
public person(string firstName,string lastName,int age){
  this.firstName=firstName;
  this.lastName=lastName;
  this.age=age;
}
//Method to get full name
public string getFullName(){
  return firstName+""+lastName;
}
}
public class practial1
{
  public static void main(string[]args)
}
//create two person object
}
//create two person object
person person1=new person("john","Doe",30);
person person2=new person("Alice","smith",25);
system.out.println("person1:"+person1.getFullName())
system.out.println("person2:"+person2.getFullName())
double averageAge=(person1.age+person2.age)/2.0;
system.out.println("Average Age:"+averageAge);
}
}
  