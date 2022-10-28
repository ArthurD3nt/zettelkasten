> The Dart team recommends going for the "initializing formal" 1 approach as it’s more readable and it initializes the variables immediately

```dart
class Fraction {
	int _enumerator;
	int _denominator;

	Fraction(this._numerator, this._denominator);
}
```

---
#IUM #flutter 2022-10-27