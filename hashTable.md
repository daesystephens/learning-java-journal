# Hash Tables

## Facts about Hash Tables:

* Hash table is a data structure that maps keys to values for highly efficient lookup.

* Hash tables are widely used in interview questions.

* Hashtable can't have null values as key.

* Hashtable search complexity can be ```O(1)``` average case and ```O(n)``` in worst case.


## Creating a Hashtable

```java
Hashtable<String, String> phoneNumber = new Hashtable<String, String>();
phoneNumber.put("Candy", "9255555555"); 
```

## Retrieving a Number

```java
String userPhoneNum = phoneNumber.get("Candy");
if (userPhoneNum != null) {
    System.out.println("Candy's number = " + userPhoneNum);
}
```