- import 'dart:io';

main() {
  print('enter the first number  ');
  int c = int.parse(stdin.readLineSync());
  print('enter  the secand number ');
  int b = int.parse(stdin.readLineSync());
  print('enter  the Opreator ');
  String o=stdin.readLineSync();
  switch(o)
  {
    case "*":
      print(c*b);
      break;
    case "-":
      print(c-b);
      break;
    case "/":
      print(c/b);
      break;
    default:
      print(c+b);
      break;
  }


