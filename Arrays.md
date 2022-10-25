>Probably you’re used to create arrays like this: 
>```java
>int[] array = new int[5];
>```
>which is the way that Java and C# offer. In Dart it doesn’t really work like that because you can only deal with collections: an "array" in Dart is represented by a `List<T>`.

```java
// 1. Array
double[] test = new test[10];
// 2. Generic
List<double> test = new ArrayList<>();
```
```dart
// 1. Array
// no equivalent
// 2. Generic
List<double> test = new List<double>();
```

## Arrays (for real this time)
> In Dart you can work with arrays but they are intended to be instances of `List<T>`.

These should be initialized with `var` or `final`
```dart
final myList = [-3.1, 5, 3.0, 4.4];
final value = myList[1]; // = 5
```

## Useful methods of `list<>` class
- `length`
- `add(T value)`
- `isEmpty`
- `contains(T value)`

---
#IUM #flutter 2022-10-25