# classEmployee
public class Employee{
   int salary, year of joining;
   string name, address;

   public int getSalary(){
       return salary;
}
   public void setSalary(int salary){
       this.salary=salary;
}
   public int getyearofjoining(){
       return yearofjoining;
}
   public void getyearofjoining(int yearofjoining){
       this.year of joining=year of joining;
}
   public string getName(){
       return name;
}
   public void setName(string name){
       this.name=name;
}
   public string getAddress(){
       return address;
}
   public void setAddress(string address){
        this.address=address;
}
public StringtoString(){
     return"Employee[name="+name+", address="+address+", salary="+salary+", yearofjoining="+yearofjoining+"];
public class Employee{
    public static void main(string args[]){
//Creating object of Employee Details class
    Employee Details emp=new Employee Details();
    emp.setName("Robert");
    emp.setYearofjoining(1994);
    emp.setAddress("64C wall street");
    emp.setSalary(15000);
    emp.setName("Sam");
    emp.setYearofjoining(2000);
    emp.setAddress("68D wall street");
    emp.setSalary(18000);
    emp.setName("John");
    emp.setYearofjoining(1999);
    emp.setAddress("26B wall street");
    emp.setSalary(22000);
    System.out.println(emp);
    }
  }
}
