## [Lesson04](../readme.md) > Exercise02: 

1. Open class [Main](../src/main/java/org/dii/oop/Main.java) in package `main.java.org.dii.oop` and edit the code to call Lesson.run() method from `exercise02`.


2. Create a Java program to find an area of shape.
* Students must be designed the program to include at least three classes: `Circle`, `Rectangle`, and `Triangle` classes and place them in the package `org.dii.oop.exercise02.Shape`.
* Designed all shape classes to have `callArea()` method. The method does its own behavior of their class, for example, the `callArea()` method of the Circle class must be calculated the area of a circle shape, and for the Triang class, the `calArea()` method must be calculated the area of a triangle shape.
* Students can use build-in class `Scanner` to get the keyboard input as shown the example below:
  ```
  Scanner in = new Scanner(System.in);
  System.out.print("Please type a string: ");
  String s = in.nextLine();
  System.out.println("You entered string " + s);
  System.out.print("Please type a int value: ");
  int a = in.nextInt();
  System.out.println("You entered integer " + a);
  System.out.print("Please type a float falue: ");
  float b = in.nextFloat();
  System.out.println("You entered float " + b);
  // closing scanner
  in.close();
  ```


 Edit class  [Lesson](../src/main/java/org/dii/oop/exercise02/Lesson.java) in package `main.java.org.dii.oop.exercise02` to write the program.


3. Run the code. The output should look like the example belows.
```
1. Circle
2. Rectangle
3. Triangle
Please select the shape [1-3] or [0] to exit: 1
Enter the radius: 5
The circle area is 78.5
```
```
1. Circle
2. Rectangle
3. Triangle
Please select the shape [1-3] or [0] to exit: 2
Enter the width: 3
Enter the height: 5
The rectangle area is 15.0
```
```
1. Circle
2. Rectangle
3. Triangle
Please select the shape [1-3] or [0] to exit: 3
Enter the base: 4
Enter the height: 6
The triangle area is 12.0
```

4. Add a `static variable` to count the number of circles, triangles, rectangles and display before terminating the program. 

```
The total number of circles is 1.
The total number of triangle is 1.
The total number of  rectangle is 1.
```
5. Add access modifier `private` to all the `static variables`, then create a method to get the value of each static variable. 
