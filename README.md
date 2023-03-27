# Lab-Flutter
import "package:flutter/material.dart";
void main() {
  runApp(ass1()); 
}
MaterialApp ass1() {
  return MaterialApp(
    home: Scaffold(
      appBar: AppBar(
        title: const Text("APP BAR"),
        centerTitle: true,
        backgroundColor: Color.fromARGB(255, 241, 151, 237),
      ),
      body: const Center(
        child: Text('Doaa Mohamed Salah',),
      ),
    ), 
  );
}
