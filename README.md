# Практическая работа по дисциплине - Разработка мобильных приложений
>Задание №1 - Что нужно сделать???!!!
```dart
void main() {
  for (var i = 0; i < 10; i++) {
    print('hello ${i + 1}');
  }
}
```
>Задание №2
```dart
void main() {
  int age = 25;
    print('значение переменной age = ${age};');
  
}
```
void main() {
  double height = 1.75;
  print('значение переменной height = ${height};');
}

void main() {
  String name = "ДПК";
  print('значение переменной name = ${name};');
}

void main() {
  bool isStudent = true;
  print('значение переменной isStudwnt = ${isStudent};');
}

void main() {
  List<int> numbers = [1,2,3,4,5];
  print('значение переменной numbers = ${numbers};');
}

void main() {
  Map<String, int> scores = {"User1": 95, "User2": 88};
  print('значение переменной scores = ${scores};');
}

void main() {
  Set<int> uniqueNumbers = {1, 2, 3, 4, 5,};
  print('значение переменной  uniqueNumbers  = ${ uniqueNumbers };');
}

void main() {
  Runes emoji = Runes('\u{1f600}');
  print('значение переменной  emoji  = ${String.fromCharCodes(emoji)}');
}

void main() {
  Symbol symbol = #mySymbol;
  print('значение переменной  symbol  = ${symbol}');
}

void main() {
  dynamic anything = "ДПК";
  print('значение переменной  anything  = ${anything}');
}

void main() {
  var message = "ДПК"; 
  print('значение переменной  message  = ${message}');
}

void main() {
  final pi = 3.14;
  print('значение переменной  pi = ${pi}');
}

void main() {
  const gravity = 9.8;
  print('значение переменной gravity = ${gravity}');
}

void main() {
 DateTime now = DateTime.now();
  print('значение переменной now = ${now}');
}

void main() {
 Duration duration = Duration(minutes: 5);
  print('значение переменной duration = ${duration}');
}

void main() {
 BigInt bigNumber = BigInt.parse('12345678901234567890');
  print('значение переменной bigNumber = ${bigNumber}');
}

void main() {
 num number = 10.5;
  print('значение переменной number = ${number}');
}

void main() {
 StringBuffer buffer = StringBuffer();
  buffer.write("Hello ");
  buffer.write("dart");
  
  print('значение переменной buffer = ${buffer.toString()}');
}

void main() {
 Uri uri = Uri.parse("https://politehdon.ru/");
  print('Значение перемнной uri = ${uri}');
}

void main() {
 int a = 100;
  int b = 10;
  
  int S = a + b;
  int V = a - b;
  int Y = a * b;
  double D = a / b;
  
  print('Сложение = ${S};');
  print('Вычитание = ${V};');
  print('Умножение = ${Y};');
  print('Деление = ${D};');
}

void main() {
  int C = 100;
 
  double F = (C * 9/5) + 32;
  
  print('Конвертация градусов цельсия в фаренгейты = ${F};');
}

import 'dart:math';
```
void main() {
  
  print(Random().nextInt(10));
}
```
