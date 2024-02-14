# Syntax of Dart Language

## The Enter Point To Application

***

void main(){
}

***

---

## Output

***

void main(){

    string name = Hany;
    int age = 21;
    int num1 = 10;
    int num2 = 20;
    print(" The message will output ");      //Output: The message will output
    print(" Name : $name and Age : $age ");  //Output: Name : Hany and Age : 21
    print(" Sum : ${ num1+num2 } ");         //Output: Sum : 30

}

***

---

## Input

***

import "dart:io";
void main(){

    print("Enter Your Name ? ");
    String x = stdin.readLineSync();
    print("Enter Your Age ? ");
    int x = int.prase(stdin.readLineSync()!);

}

***
