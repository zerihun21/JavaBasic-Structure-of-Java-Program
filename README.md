# JavaBasic-Structure-of-Java-Program


|||
|--- |--- |
|public class Hello|This creates a class called Hello.
            All class names must start with a capital letter.
            The public word means that it is accessible from any other classes.|
|/* Comments */|The compiler ignores comment block. Comment can be used anywhere in the program to add info about the program or code block, which will be helpful for developers to understand the existing code in the future easily.|
|Braces|Two curly brackets {...} are used to group all the commands, so it is known that the commands belong to that class or method.|
|public static void main|When the main method is declared public, it means that it can also be used by code outside of its class, due to which the main method is declared public.
            The word static used when we want to access a method without creating its object,  as we call the main method, before creating any class objects.
            The word void indicates that a method does not return a value. main() is declared as void because it does not return a value.
            main is a method; this is a starting point of a Java program.
         
         You will notice that the main method code has been moved to some spaces left. It is called indentation which used to make a program easier to read and understand.|
|String[] args|It is an array where each element of it is a string, which has been named as "args". If your Java program is run through the console, you can pass the input parameter, and main() method takes it as input.|
|System.out.println();|This statement is used to print text on the screen as output, where the system is a predefined class, and out is an object of the PrintWriter class defined in the system. The method println prints the text on the screen with a new line. You can also use print() method instead of println() method. All Java statement ends with a semicolon.|
