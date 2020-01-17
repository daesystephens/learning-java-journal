# STACK
Stack is a data structure that uses the principal called **LIFO** Last-In-First-Out.</br>
This means the last element added to the stack must be the first one to be removed.

**Assigning a Stack**
```java
Deque<Integer> stack = new ArrayDeque<Integer>();
```

## STACK METHODS 
**Tests if this stack is empty.**
This will return a boolean true or false
```java
STACK.empty();
```

**Looks at the object at the top of this stack without removing it from the stack.**
This will return the value at the top of the stack
```java
STACK.peek();
```

**Removes the object at the top of this stack and returns that object as the value of this function.**
```java
STACK.pop();
```


**Pushes an item onto the top of the stack.**
```java
push(E item);
```

# QUEUE
Queue is a data structure that uses a principle called **FIFO** First-In-First-Out.</br>
This means the first object added to the queue must be the first one to be removed.

**Assigning a Queue**
```java
Queue<Integer> q = new LinkedList<>();
``` 

**Add**
this will add at the end of the line.
```java
q.add(i);
```

**Remove**
this will remove the first element.
```java
q.remove(); 
```

**Peek**
this will display the value of head or first item
```java
q.peek(); 
```

**Size**
```java
q.size();
```

![stackqueue](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2018/07/Computer-science-fundamentals_6.1.png)
