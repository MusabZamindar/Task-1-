Question 1

Write a Dart program that prints “Hello, World!”.

Answer:

void main() {
  print("Hello, World!");
}

Output:

Hello, World!

Question 2

Write a Dart program to perform the following operations on two numbers a = 10 and b = 5:
	•	Sum
	•	Difference
	•	Product
	•	Quotient

Answer:

void main() {
  int a = 10, b = 5;
  print("Sum: ${a + b}");
  print("Difference: ${a - b}");
  print("Product: ${a * b}");
  print("Quotient: ${a / b}");
}

output
Sum: 15  
Difference: 5  
Product: 50  
Quotient: 2.0  

Question 3

Write a Dart program to check if a given number is odd or even:
	•	Define a variable num = 11.
	•	Print “Even” if the number is even.
	•	Print “Odd” if the number is odd.

Answer:

void main() {
  int num = 11;
  print(num % 2 == 0 ? "Even" : "Odd");
}

Output:

Odd

Question 4

Write a Dart program to perform addition, subtraction, multiplication, and division using functions.
	•	Use a = 8 and b = 4.

Answer:

int add(int a, int b) => a + b;
int sub(int a, int b) => a - b;
int mul(int a, int b) => a * b;
double div(int a, int b) => a / b;

void main() {
  int a = 8, b = 4;
  print("Sum: ${add(a, b)}");
  print("Difference: ${sub(a, b)}");
  print("Product: ${mul(a, b)}");
  print("Quotient: ${div(a, b)}");
}

Output:

Sum: 12  
Difference: 4  
Product: 32  
Quotient: 2.0   

Question 5 
i was getting some errors

Question 6

Write a Dart program to:
	1.	Create a list of integers: [5, 3, 8, 1, 2].
	2.	Add the number 7 to the list.
	3.	Sort the list in ascending order.
	4.	Print the sorted list.

Answer:

void main() {
  List<int> numbers = [5, 3, 8, 1, 2];
  numbers.add(7);
  numbers.sort();
  print(numbers);
}

Output:

[1, 2, 3, 5, 7, 8]

Question 7

Write a Dart program to:
	1.	Create a set of unique integers: {1, 2, 3, 4}.
	2.	Add a new number 5 to the set.
	3.	Remove the number 2 from the set.
	4.	Print the final set.

Answer:

void main() {
  var numbers = {1, 2, 3, 4};
  numbers.add(5);
  numbers.remove(2);
  print(numbers);
}

Output:

{1, 3, 4, 5}

Question 8

Write a Dart program to:
	1.	Create a map with the following key-value pairs: {'name': 'Alice', 'age': 25, 'city': 'New York'}.
	2.	Add a new key-value pair: 'country': 'USA'.
	3.	Update the value of 'age' to 26.
	4.	Print the updated map.

Answer:

void main() {
  var person = {'name': 'Alice', 'age': 25, 'city': 'New York'};
  person['country'] = 'USA';
  person['age'] = 26;
  print(person);
}

Output:

{name: Alice, age: 26, city: New York, country: USA}

Question no 9 and 10 i was not able to solve

Question 11

Write a Dart program to create a class Car with the following properties:
	•	brand (String)
	•	model (String)
	•	year (int)

Add a method displayInfo() that prints the car’s details. Create an object of the Car class and call the displayInfo() method.

Answer:

class Car {
  String brand;
  String model;
  int year;

  Car(this.brand, this.model, this.year);

  void displayInfo() {
    print('Brand: $brand, Model: $model, Year: $year');
  }
}

void main() {
  var car = Car('Toyota', 'Corolla', 2020);
  car.displayInfo();
}

Output:

Brand: Toyota, Model: Corolla, Year: 2020

Question 12

Write a Dart program to demonstrate inheritance.
	•	Create a base class Animal with a method makeSound() that prints “Animal makes a sound”.
	•	Create a derived class Dog that overrides the makeSound() method to print “Dog barks”.

Answer:

class Animal {
  void makeSound() {
    print("Animal makes a sound");
  }
}

class Dog extends Animal {
  @override
  void makeSound() {
    print("Dog barks");
  }
}

void main() {
  var dog = Dog();
  dog.makeSound();
}

Output:

Dog barks

Question no 13,14 and 15 i was not able to solve
