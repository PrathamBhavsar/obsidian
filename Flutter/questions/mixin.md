**mixins** are normal classes from which we can borrow methods(or variables) from without extending the class. In dart we can do this by using the keyword `with`

its a way to define code that can be used in multiple class hierarchies

``` dart
mixin Musical {
void playInstrument(String instrumentName); // Abstract Method

void playPiano() {
	playInstrument('Piano');
	}

void playFlute() {
	playInstrument('Flute');
	}

}

class Musician with Musical {
@override
void playInstrument(String instrumentName) { //Subsclass must define
		print('plays $instrumnetName');
	}
}
```

``` dart
class A {
method() {}
}

class B with A {}

void main() {
B b = B();
b.method();
}
```