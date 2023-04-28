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
   So in the children class can just do ``this`` which will brings the values to parent class betweeen the 2 files. As the player is inputing the values.
   
   ### Recursion
   Recursion is like something that run true a condition until it ture and print it out.
   
   For example in this code:
   ```JS
   public static String stringReverse(String word)
  {
    if (word.length() == 0)
    {
      return word;
    }
    return stringReverse(word.substring(1)) + word.substring(0,1);
  }
```
We need to Reverse a word right let give it ``apple`` for example. so a is 0, p is 1, p is 2, l is 3, e is 4. the first letter is getting print out is a is in placed than we remove it than p after that the other p and than l and e. then we printed everything out So the reversed word will look like ``elppa``.

### Challenge
Something I struggle on was recursion it was super confusing and very hard to understand. I feel I didnt even explain the code right above. I ask alot of my friends for help to further understanding of the code. This is my first time looking into recursion and it was not fun. I also think we didnt get enough practice on it because there were only one coding activity for us to try.

```JS 
public class U10_L2_Activity_One
{

  public static String stringReverse(String word)
  {
    if (word.length() == 0)
    {
      return word;
    }
    return stringReverse(word.substring(1)) + word.substring(0,1);
  }

}
```
The task look simple enough reverse the word. At first I was using a for loops to do this but I relize that didnt work on project stem since they wanted us to use recursion which I kinda sturggle, but finding out that we need to find the first letter and printed out and than printed the next letter buy removing the first letter. So that why we have ``word.length() == 0`` becuase the first letter in a ``array`` is always a 0. I am going to be honest I completely gave up coding assignment trying to brain stroming and thinking about the code and how can I write it out. At the end I just gave up it was probably the only one assignment I didnt finshed.







    
