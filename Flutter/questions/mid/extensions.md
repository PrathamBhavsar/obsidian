these methods allow devs to add new methods to existing classes without changing their original implementation

easy to implement

``` dart
extension StringExtensions on String {
  String capitalize() {
    if (isEmpty) return this;
    return this[0].toUpperCase() + substring(1);
  }
}

void main() {
  String text = "hello";
  print(text.capitalize()); // Output: Hello
}

```

