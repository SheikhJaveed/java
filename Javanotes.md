# JAVA 
## About java


![Alt text](<java image.png>)
1. A sample java code

```  java
public class pattern1{
    public static void main(String[] args){
        //square pattern
        for(int i=1;i<=4;i++){
            for(int j=1;j<=5;j++){
                System.out.print("*");
            }
        System.out.println(); //for next line 
        }
    }
}  
```


___

[Link to this folder](basic1.java)
---
# Basic datatypes

| Datatype | Default value | Default size |
|--- | --- | --- |
|boolean|false|1 bit|
|char|'u0000'|2 byte|
|byte|0|1 byte|
|short|0|2 byte|
|int|0|4 byte|
|long|0L|8 byte|
|float|0.0f|4 byte|
|double|0.0d|8 byte|
|

## Note
### Why if we declare a float variable in Java we write f as (3.14f)?

Because without the “f” the number would be implicitly created as double. There are things called literals[1] which are helpful to specify the exact data type for a hardcoded number.

## Difference between .compareto() and .equals() function
The 2 main differences are that: equals will take any Object as a parameter, but compareTo will only take Strings. equals only tells you whether they're equal or not, but compareTo gives information on how the Strings compare lexicographically.
### lexicographically 
sorted in a way that uses an algorithm based on the alphabetical order used in dictionaries.

![Alt text](<lexicographical order.png>)

## parseInt()
The method parseInt() belongs to the Integer class which is under java. lang package. It is used to parse the string value as a signed decimal value. It is used in Java for converting a string value to an integer by using the method parseInt().
## toString()
The toString() method of the Object class returns the string representation of an object in Java. If we print any object, the Java Compiler internally invokes the toString() method on that object. The value returned by the toString() method is then printed.

ALWAYS REMEMBER : Java Strings are Immutable.

