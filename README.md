# Process Writeup

## Name: Anson
## Course: APCSA(Java)
## Period: 6
## Concept:  Inheritance, Recursion

### Context 
 In unit 9 where learn about Inheritance which is base on child classes and parent classes. Than we learn about Recursion which having a set of code running over and over again until it reach to a certain point, at the end it adds it all up to find the final vaules. Recursion is really confusing and I really dont understand it that much.
 
 ### Inheritance
 * ``extends`` is like connecting to the parent class and bring the data from that files over. like your allow to use the data from that files.

Let show example of using extends:

```Js
public class Coffee
{
  private String size;
  private boolean isSkinny;
  private int shots;
  private String type;

  public Coffee()
  {
    this("small", false, 1, "latte");
  }

  public Coffee(String size, boolean isSkinny, int shots, String type)
  {
    this.size = size;
    this.isSkinny = isSkinny;
    this.shots = shots;
    this.type = type;
  }
  ``` 
  This is the parent class where it has all the vaariables and been set into a boolean int and string depending they belog.
  ```Js 
  public class SpecialityCoffee extends Coffee{
  private String flavor;
   public SpecialityCoffee(){
     super();
     flavor = "vanilla";
   }
   public SpecialityCoffee(String size, String type, String flavor){
     this(size, false, 1, type, flavor);
   }
   ``` 
   So in the children class can just do ``this`` which will brings the values to parent class betweeen the 2 files.
   
