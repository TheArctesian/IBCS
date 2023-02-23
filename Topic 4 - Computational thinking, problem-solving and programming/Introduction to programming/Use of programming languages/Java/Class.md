Classes are used to define new data types

Java classes define 
- Attributes 
	- What the class knows 
- Behaviors 
	- What the class can do

Each class has constructors used to initialize attribute in a newly created [[object]]

we can create a simple class like such

```java
public class Turtle
{
    //properties
    private String color;
    private int weight;
     private int length;
    private String sound;

    //constructor
    public Turtle()
    {
        color = "red";
        weight = 95;
        length = 30;
        sound = "merawr";
    }

    public Turtle(String , int someLength, int someWeight, String someSound)
    {
        color = someColor;
        length = someLength;
        weight = someWeight;
        sound = someSound;
    }
}
```

and instantiate objects with 
```java
Turtle jeff = new Turtle(); //Will inherit default constructor
Turtle bigBoi = new Turtle("blue", 1000, 500, "graaaawr");
```
