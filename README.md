# EXP8_Using-Inheritance-one-class-can-acquire-the-properties-of-others.
## AIM:
### To create a program using inheritance and aquire the properties into another class.
## PROCEDURE:
### 1.Create the class and declare the main method so that the JVM will identify the main program to run.
### 2.Create another class and use the keyword EXTENDS to use the concept of INHERITANCE.
### 3.Print a statement to check whether the inner class is accessable or not. 
### 4.If the extended class's statement is executed then,this program follows the concept of inheritance.
### 5.The program will be executed after the compilation and results are printed.
## PROGRAM:
```
// NAME: PAVITHRA G
// ROLLNO: 212221240036
package ten;

public class Main_2 {
    public static void main(String [] args){
        Color c;
        c= new Redpaint();
        c.paint();
    }
}
package ten;

public class Color {
    void paint() {
        System.out.println("Painting");
    }
}
class Redpaint extends Color{
    void paint(){
        System.out.println("Red paint");
    }
}

```

## RESULT:
![image](https://github.com/gpavithra673/EXP8_Using-Inheritance-one-class-can-acquire-the-properties-of-others./assets/93427264/26d47163-25fc-4264-9a7b-f1524b20116f)
