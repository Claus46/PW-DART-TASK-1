# Практическая работа по дисциплине - Разработка мобильных приложений
>Задание №1 - Что нужно сделать???!!! - от 1 до 10 привет мир.
```dart
void main() {
  for (var i = 0; i < 10; i++) {
    print('hello ${i + 1}');
  }
}
```
>Задание №2 - значение переменной
```dart
void main() {
  int age = 25;
    print('значение переменной age = ${age};');
  
}
```
>Задание №3 - значение переменной double
```dart
void main() {
  double height = 1.75;
  print('значение переменной height = ${height};');
}
```
>Задание №4 - значение переменной String
```dart
void main() {
  String name = "ДПК";
  print('значение переменной name = ${name};');
}
```
>Задание №5 - значение переменной true/false
```dart
void main() {
  bool isStudent = true;
  print('значение переменной isStudwnt = ${isStudent};');
}
```
>Задание №6 - numbers
```dart
void main() {
  List<int> numbers = [1,2,3,4,5];
  print('значение переменной numbers = ${numbers};');
}
```
>Задание №7 - значение нескольких переменных scores 
```dart
void main() {
  Map<String, int> scores = {"User1": 95, "User2": 88};
  print('значение переменной scores = ${scores};');
}
```
>Задание №8 - uniqueNumbers 
```dart
void main() {
  Set<int> uniqueNumbers = {1, 2, 3, 4, 5,};
  print('значение переменной  uniqueNumbers  = ${ uniqueNumbers };');
}
```
>Задание №9 - Эмоджи
```dart
void main() {
  Runes emoji = Runes('\u{1f600}');
  print('значение переменной  emoji  = ${String.fromCharCodes(emoji)}');
}
```
>Задание №10
```dart
void main() {
  Symbol symbol = #mySymbol;
  print('значение переменной  symbol  = ${symbol}');
}
```
>Задание №11
```dart
void main() {
  dynamic anything = "ДПК";
  print('значение переменной  anything  = ${anything}');
}
```
>Задание №12
```dart
void main() {
  var message = "ДПК"; 
  print('значение переменной  message  = ${message}');
}
```
>Задание №13
```dart
void main() {
  final pi = 3.14;
  print('значение переменной  pi = ${pi}');
}
```
>Задание №14
```dart
void main() {
  const gravity = 9.8;
  print('значение переменной gravity = ${gravity}');
}
```
>Задание №15
```dart
void main() {
 DateTime now = DateTime.now();
  print('значение переменной now = ${now}');
}
```
>Задание №16
```dart
void main() {
 Duration duration = Duration(minutes: 5);
  print('значение переменной duration = ${duration}');
}
```
>Задание №17
```dart
void main() {
 BigInt bigNumber = BigInt.parse('12345678901234567890');
  print('значение переменной bigNumber = ${bigNumber}');
}
```
>Задание №18
```dart
void main() {
 num number = 10.5;
  print('значение переменной number = ${number}');
}
```
>Задание №19
```dart
void main() {
 StringBuffer buffer = StringBuffer();
  buffer.write("Hello ");
  buffer.write("dart");
  
  print('значение переменной buffer = ${buffer.toString()}');
}
```
>Задание №20
```dart
void main() {
 Uri uri = Uri.parse("https://politehdon.ru/");
  print('Значение перемнной uri = ${uri}');
}
```
>Задание №21
```dart
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
```
>Задание №22
```dart
void main() {
  int C = 100;
 
  double F = (C * 9/5) + 32;
  
  print('Конвертация градусов цельсия в фаренгейты = ${F};');
}
```
>Задание №23
```dart
import 'dart:math';

void main() {
  
  print(Random().nextInt(10));
}
```
>Задание №24
```dart
bool a(int number){
   return number % 2 == 0;
}
bool b(int number){
   return number % 2 != 0;
}
void main() {
  int a1 = 2;
  int b1 = 3;
  print('Четное = ${a(a1)};');
  print('Не четное = ${b(b1)};');
}
```
