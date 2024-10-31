
# StringBuilder Functions in Java

The `StringBuilder` class in Java provides a mutable sequence of characters, making it efficient for string manipulation, especially in DSA problems. Below are commonly used `StringBuilder` functions along with example's.

---

### 1. `append(String str)`
- **Description**: Adds the specified string to the end of the `StringBuilder`.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello");
  sb.append(" World");
  System.out.println(sb); // Output: Hello World
  ```

---

### 2. `insert(int offset, String str)`
- **Description**: Inserts the given string at the specified position.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello");
  sb.insert(0, "Java ");
  System.out.println(sb); // Output: Java Hello
  ```

---

### 3. `delete(int start, int end)`
- **Description**: Removes the substring from the specified start to end index.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Java Hello");
  sb.delete(0, 5);
  System.out.println(sb); // Output: Hello
  ```

---

### 4. `deleteCharAt(int index)`
- **Description**: Deletes the character at the specified index.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello World");
  sb.deleteCharAt(5);
  System.out.println(sb); // Output: HelloWorld
  ```

---

### 5. `setCharAt(int index, char ch)`
- **Description**: Sets the character at the specified index to the given character.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello");
  sb.setCharAt(0, 'Y');
  System.out.println(sb); // Output: Yello
  ```

---

### 6. `reverse()`
- **Description**: Reverses the sequence of characters in the `StringBuilder`.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello");
  sb.reverse();
  System.out.println(sb); // Output: olleH
  ```

---

### 7. `toString()`
- **Description**: Converts the `StringBuilder` content to a `String`.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello World");
  String result = sb.toString();
  System.out.println(result); // Output: Hello World
  ```

---

### 8. `length()`
- **Description**: Returns the length of the `StringBuilder`.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello");
  int length = sb.length();
  System.out.println(length); // Output: 5
  ```

---

### 9. `charAt(int index)`
- **Description**: Returns the character at the specified index.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello");
  char ch = sb.charAt(1);
  System.out.println(ch); // Output: e
  ```

---

### 10. `substring(int start, int end)`
- **Description**: Returns a substring from the specified start index to end index.
- **Example**:
  ```java
  StringBuilder sb = new StringBuilder("Hello World");
  String sub = sb.substring(1, 4);
  System.out.println(sub); // Output: ell
  ```

---

These functions make `StringBuilder` a powerful tool for manipulating strings efficiently in Java.
