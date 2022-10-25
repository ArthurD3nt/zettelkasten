## Parsing
![[Pasted image 20221025115653.png]]
![[Pasted image 20221025115733.png]]
`.parse()` is deprecated use `.tryParse()` instead

## Strings
> [...] combining expressions into strings by using ${expr} (a shorthand to call the toString() method). 
![[Pasted image 20221025121150.png]]

> A string can be either single or multiline. Single line strings are shown above using single or double quotes, and multiline strings are written using triple quotes.
![[Pasted image 20221025121321.png]]

## Nullable e non-nullable types
Di default Dart è **null-safe** ma esistono tipi *nullable*:
```dart
// nullable
int? value;
print("$value"); //epression is legal and prints 'null'

// non-nullable
int value;
print("$value"); //epression is illegal and error :(
```

Nullable Indexed stuff:
```dart
String? name;
String? first = name?[0]; //first = 'null'
```

## Type test
![[Pasted image 20221025211256.png]]


---
#IUM #flutter 2022-10-25