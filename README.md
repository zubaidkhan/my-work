# Hi, I'm Zubaid Khan 👋
- 💻 BSCS Final Year Student at Hazara University Mansehra
- 📱 Learning Flutter for Mobile App Development
- 🚀 Interested in Full-Stack Development
- 🔗 Check out my coding below: 

Welcome to my GitHub repository, where I document my journey in Dart programming. As I navigate the learning phase of Flutter development, I store every program and piece of code I have worked on using Dart in Android Studio. This repository reflects my progress, showcasing my hands-on practice and continuous improvement in writing efficient and scalable applications. Feel free to explore my work and join me on this learning journey!  

 Basic code of Dart Language:


1) void main() {
  print("Hello, World!");
}

2) void main() {
  String name = "Zubaid Khan"; // String
  int age = 22; // Integer
  double height = 5.9; // Decimal number
  bool isStudent = true; // Boolean

  print("Name: $name");
  print("Age: $age");
  print("Height: $height");
  print("Student: $isStudent");
}


3) void main() {
  int marks = 75;

  if (marks >= 80) {
    print("Grade: A");
  } else if (marks >= 60) {
    print("Grade: B");
  } else {
    print("Grade: C");
  }
}

4) Loops
   
   for loop:
   
void main() {
  for (int i = 1; i <= 5; i++) {
    print( i);
  }
}

while loop:

void main() {
  int i = 1;
  while (i <= 6) {
    print(i);
    i++;
  }
}

Do-While Loop 
void main() {
  int i = 1;
  do {
    print("zubaid khan Dart");
    i++;
  } while (i <= 5);
}


6)  Classes and Objects
class Person {
  String name;
  int age;

  Person(this.name, this.age);

  void display() {
    print("Name: $name, Age: $age");
  }
}

void main() {
  Person person = Person("Zubaid Khan", 22);
  person.display();
}

FLUTTER:
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      title: 'Weather Crew App',
      theme: ThemeData(
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.lightBlue),
        useMaterial3: true,
      ),
      home: const MyHomePage(title: 'Home'),
    );
  }
}

class MyHomePage extends StatelessWidget {
  const MyHomePage({super.key, required this.title});

  final String title;

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        backgroundColor: Colors.blue,
        title: Text(title),
      ),
      body:
Center(
  child: Container(
    width: 200,
    height:200,
    color: Colors.blue,
  ),

)
    );


  }
}

Apologies for not uploading my Flutter code to this repository yet. I have been actively working on various Dart programs in Android Studio, including my project Weather Crew Application, but I haven’t had the chance to organize and push them here. I have a solid understanding of Flutter basics, including widgets, buttons, and other essential components. I’ll be updating this space soon with my projects and practice codes. Stay tuned!
