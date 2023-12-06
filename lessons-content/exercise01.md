## [Lesson01](../readme.md) > Exercise01:

1. Open class [Main](../src/main/java/org/dii/oop/Main.java) in package `main.java.org.dii.oop` and edit the code as display below:
   ```
   package main.java.org.dii.oop;

   import main.java.org.dii.oop.exercise01.Lesson;

   public class App {
     public static void main(String[] args) {
       Lesson.run();
    }
   }
   ```

2. Creates a package called `main.java.org.dii.oop.exercise01.animals`. 

(**Note:** *The names of packages is a lower-case letters to avoid any conflicts with the names of classes*) 

3. Create the Mammal class as shown below:
     ```
     package main.java.org.dii.oop.exercise03.animal;

     public class Mammal {

       String name;
       public void eat() {
         System.out.println("Mammal eats");
       }
    
       public void travel() {
         System.out.println("Mammal travels");
       }
     }

     ```


3. Edit class  [Lesson](../src/main/java/org/dii/oop/exercise01/Lesson.java) in package `org.dii.oop.lesson02.exercise03` and follow the instructions.


4. Run the code:
```
John
Mammal eats
Mammal travels
```