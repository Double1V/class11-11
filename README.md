# class11-11

## kata task1

[Task link](https://www.codewars.com/kata/544675c6f971f7399a000e79)    
My solution
```java
  public class StringToNumber {
    public static int stringToNumber(String str) {
        return Integer.parseInt(str);
    }
}
```
My fav solution
```java
 public class StringToNumber {
  public static int stringToNumber(String str) {
    return Integer.valueOf(str);
  }
}
```

## kata task2

[Task link](https://www.codewars.com/kata/52fba66badcd10859f00097e)    
My solution
```java
public class Troll {
    public static String disemvowel(String str) {
        return str.replaceAll("(?i)[aeiou]", "");
    }
}
```
My fav solution
```java
public class Troll {
  public static String disemvowel(String str) {
      return str.replaceAll("[aAeEiIoOuU]", "");
  } 
}
```
