# lastMinuteJavaSyntax

## Important Syntax in java

### String Class

Syntax - Taking s1 if one String and (s1,s2) if two strings are required.

| No. | Methods                                                 | Description                                                       |
| --- | ------------------------------------------------------- | ----------------------------------------------------------------- |
| 1   | `char s1.charAt(int index)`                             | returns char value for the particular index                       |
| 2   | `int s1.length()`                                       | returns string length                                             |
| 3   | `String s1.substring(int beginIndex)`                   | returns substring for given begin index.                          |
|     | `String s1.substring(int beginIndex, int endIndex)`     | returns substring for given begin index and end index.            |
| 4   | `boolean s1.contains(CharSequence s)`                   | returns true or false after matching the sequence of char value.  |
| 5   | `boolean s1.equals(Object another)`                     | checks the equality of string with the given object.              |
| 6   | `boolean s1.isEmpty()`                                  | checks if string is empty.                                        |
| 7   | `String s1.concat(String str)`                          | concatenates the specified string.                                |
| 8   | `String s1.replace(char old, char new)`                 | replaces all occurrences of the specified char value.             |
|     | `String s1.replace(CharSequence old, CharSequence new)` | replaces all occurrences of the specified CharSequence.           |
| 9   | `String s1.equalsIgnoreCase(String another)`            | compares another string. It doesn't check case.                   |
| 10  | `String[] s1.split(String regex)`                       | returns a split string matching regex.                            |
|     | `String[] s1.split(String regex, int limit)`            | returns a split string matching regex and limit.                  |
| 11  | `int s1.indexOf(int ch)`                                | returns the specified char value index.                           |
|     | `int s1.indexOf(int ch, int fromIndex)`                 | returns the specified char value index starting with given index. |
|     | `int s1.indexOf(String substring)`                      | returns the specified substring index.                            |
|     | `int s1.indexOf(String substring, int fromIndex)`       | returns the specified substring index starting with given index.  |
| 12  | `String s1.toLowerCase()`                               | returns a string in lowercase.                                    |
| 13  | `String s1.toUpperCase()`                               | returns a string in uppercase.                                    |
| 14  | `String s1.trim()`                                      | removes the beginning and ending spaces of this string.           |
| 15  | `String String.valueOf(int value)`                      | converts the given type into string. It is an overloaded method.  |

### Math Class

If the return type is of the type same as an argument then we are using _var_

| No. | Methods                                                         | Description                                                                                                    |
| --- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| 1   | `var Math.abs(a)`                                               | return the Absolute value of the given value.                                                                  |
| 2   | `var Math.max(a,b)`                                             | returns the Largest of two values.                                                                             |
| 3   | `long Math.round(float/double x)`                               | round off the decimal numbers to the nearest value.                                                            |
| 4   | `double Math.sqrt(double x)`                                    | return the square root of a number.                                                                            |
| 5   | `double Math.cbrt(double x) `                                   | return the cube root of a number.                                                                              |
| 6   | `double Math.pow(double a, double b) `                          | returns the value of first argument raised to the power to second argument.                                    |
| 7   | `double Math.signum(a) => (a>0): 1.0 / (a<0): -1.0 / (a==0): 0` | used to find the sign of a given value.                                                                        |
| 8   | `double Math.ceil(double x)`                                    | used to find the smallest integer value that is greater than or equal to the argument or mathematical integer. |
| 9   | `double Math.floor(double a)`                                   | used to find the largest integer value which is less than or equal to the argument                             |
| 10  | `double Math.random()`                                          | returns a double value with a positive sign, greater than or equal to 0.0 and less than 1.0.                   |
| 11  | `double Math.log(double x)`                                     | returns the natural logarithm.                                                                                 |
| 12  | `double Math.log10(double x)`                                   | return the base 10 logarithm of a double value.                                                                |
| 13  | `double Math.exp(double x) `                                    | returns E raised to the power of a double value                                                                |
| 14  | `double Math.sin/cos/tan/asin/acos/atan(double a)`              | return the trigonometric value.                                                                                |
| 15  | `double sinh/tanh/cosh(double x) `                              | return the trigonometric Hyperbolic value.                                                                     |

### Integer Class

| No. | Methods                                                                       | Description                                                                                                                                                |
| --- | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | `int Integer.compare(int x,int y)`                                            | ?                                                                                                                                                          |
| 2   | `int x.compareTo(int x)`                                                      | ?                                                                                                                                                          |
| 3   | `boolean Integer.equals(Object obj) `                                         | compares the value of the parameter to the value of the current Integer object and returns boolean ( True or False ).                                      |
| 4   | `int object.intValue() `                                                      | returns the value of the specified number as an int.                                                                                                       |
| 5   | `long object.longValue()`                                                     | returns the value of the specified number as an long.                                                                                                      |
| 6   | `int Integer.parseInt (String s) `                                            | parses the String argument as a signed decimal integer object                                                                                              |
|     | `int Integer.parseInt (String s, int radix) `                                 | parses the String argument as a signed decimal integer object in the specified radix by the second argument                                                |
|     | `int Integer.parseInt (CharSequence s,int beginIndex,int endIndex,int radix)` | parses the CharSequence argument as a signed integer in the specified radix argument, beginning at the specified beginIndex and extending to endIndex - 1. |
| 7   | `int Integer.reverse(int i) `                                                 | method returns the numeric value obtained by reversing order of the bits in the specified int value.                                                       |
| 8   | `int Integer.rotateLeft(int i, int distance)`                                 | returns the value obtained by rotating the two's complement binary representation of the specified int value left by the specified number of bits.         |
|     | ` int Integer.rotateRight(int i, int distance)`                               | returns the value obtained by rotating the two's complement binary representation of the specified int value right by the specified number of bits.        |
| 9   | `int Integer.signum(int i)`                                                   | (a>0): 1.0 / (a<0): -1.0 / (a==0): 0                                                                                                                       |
| 10  | `String Integer.toBinaryString (int i)`                                       | returns a string representation of the integer argument as an unsigned integer in binary base 2.                                                           |
|     | `String Integer.toHexString (int i) `                                         | returns a string representation of the integer argument as an unsigned integer in binary base 16.                                                          |
|     | `String Integer.toOctalString (int i)`                                        | returns a string representation of the integer argument as an unsigned integer in binary base 8.                                                           |
| 11  | `String a.toString()`                                                         | returns a String object representing the value of the Number Object.(int/float/double/boolean etc)                                                         |
|     | `String Integer.toString(int i) `                                             | returns a string representation of the int type argument in base 10.                                                                                       |
|     | `String Integer.toString(int i, int radix)`                                   | returns a string representation of the int type argument in the specified radix.(First int to radix conversion)                                            |
| 12  | `Integer Integer.valueOf(int i)`                                              | returns the relevant Integer Object holding the value of the argument passed.                                                                              |
|     | `Integer Integer.valueOf(String s)`                                           | returns the relevant Integer Object holding the value of the argument passed.                                                                              |
|     | `Integer Integer.valueOf(String s, int radix)`                                | convert to int and chnages be base from radix to 10.                                                                                                       |

\*valueOf is present in both Integer and String, Integer.valueOf() give Integer and String.valueOf() gives String

### ArrayList

Syntax: ArrayList <E> x = new ArrayList<E>();

| No. | Methods                                          | Description                                                                                                                                                         |
| --- | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | `int x.size()`                                   | returns length of an ArrayList                                                                                                                                      |
| 2   | `void x.add(int index, E element)`               | used to insert the specified element at the specified position in a list.                                                                                           |
| 3   | `boolean x.add(E e)`                             | used to append the specified element at the end of a list.                                                                                                          |
| 4   | `boolean x.addAll(Collection c) `                | used to append all of the elements in the specified collection to the end of this list, in the order that they are returned by the specified collection's iterator. |
| 5   | `boolean x.addAll(int index, Collection c)`      | used to append all the elements in the specified collection, starting at the specified position of the list.                                                        |
| 6   | `void x.clear()`                                 | used to remove all of the elements from this list.                                                                                                                  |
| 7   | `E x.get(int index)`                             | used to fetch the element from the particular position of the list.                                                                                                 |
| 8   | `boolean x.isEmpty()`                            | returns true if the list is empty, otherwise false.                                                                                                                 |
| 9   | `Object[] x.toArray()`                           | used to return an array containing all of the elements in this list in the correct order.                                                                           |
| 10  | `Object x.clone()`                               | used to return a shallow copy of an ArrayList.                                                                                                                      |
| 11  | `boolean x.contains(Object o)`                   | returns true if the list contains the specified element                                                                                                             |
| 12  | `int x.indexOf(Object o)`                        | used to return the index in this list of the first occurrence of the specified element, or -1 if the List does not contain this element.                            |
| 13  | `E x.remove(int index)`                          | to remove the element present at the specified position in the list.                                                                                                |
| 14  | `boolean x.remove(Object o)`                     | used to remove the first occurrence of the specified element.                                                                                                       |
|     | `boolean x.removeAll(Collection c)`              | used to remove all the elements from the list.                                                                                                                      |
| 15  | `void x.removeRange(int fromIndex, int toIndex)` | to remove all the elements lies within the given range.                                                                                                             |
| 16  | `E x.set(int index, E element)`                  | used to replace the specified element in the list, present at the specified position.                                                                               |
| 17  | `void x.sort(Comparator<? super E> c)`           | used to sort the elements of the list on the basis of specified comparator.                                                                                         |
| 18  | `List<E> subList(int fromIndex, int toIndex)`    | used to fetch all the elements lies within the given range.                                                                                                         |

### LinkedList

Syntax: LinkedList<E> x =new LinkedList<E>();  
 E: data type

| No. | Methods                                        | Description                                                                                                                                                         |
| --- | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | `boolean x.add(E e)`                           | to append the specified element to the end of a list.                                                                                                               |
| 2   | `void x.add(int index, E element)`             | to insert the specified element at the specified position index in a list.                                                                                          |
| 3   | `boolean x.addAll(Collection <E> c)`           | used to append all of the elements in the specified collection to the end of this list, in the order that they are returned by the specified collection's iterator. |
|     | `boolean x.addAll(int index, Collection<E> c)` | used to append all the elements in the specified collection, starting at the specified position of the list.                                                        |
| 4   | `void x.addFirst(E e)`                         | used to insert the given element at the beginning of a list.                                                                                                        |
|     | `void x.addLast(E e)`                          | used to append the given element to the end of a list.                                                                                                              |
| 5   | `void x.clear()`                               | used to remove all the elements from a list.                                                                                                                        |
| 6   | `Object x.clone()`                             | used to return a shallow copy of an ArrayList.                                                                                                                      |
| 7   | `boolean x.contains(Object o)`                 | used to return true if a list contains a specified element.                                                                                                         |
| 8   | `E x.element()`                                | used to retrieve the first element of a list.                                                                                                                       |
| 9   | `E x.get(int index)`                           | used to return the element at the specified position in a list.                                                                                                     |
| 10  | `int x.indexOf(Object o)`                      | used to return the index in a list of the first occurrence of the specified element, or -1 if the list does not contain any element.                                |
| 11  | `boolean x.offer(E e)`                         | adds the specified element as the last element of a list.                                                                                                           |
| 12  | `E x.peek()`                                   | retrieves the first element of a list                                                                                                                               |
|     | `E x.poll()`                                   | It retrieves and removes the first element of a list.                                                                                                               |
| 13  | `int x.size()`                                 | used to return the number of elements in a list.                                                                                                                    |
| 14  | `E x.set(int index, E element)`                | It replaces the element at the specified position in a list with the specified element.                                                                             |
| 15  | `E x.remove(int index)`                        | used to remove the element at the specified position in a list.                                                                                                     |

### Map

![Alt text](./java-map-hierarchy.png "Title")
