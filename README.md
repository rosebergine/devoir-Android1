# devoir-Android1
import "package:flutter/material.dart";

void main(){
  runApp(MyApp());
}

class MyApp extends StatelessWidget{
  Widget build(BuildContext context){
    return MaterialApp(
      home: HomeScreen(),
    );
  }
}

class HomeScreen extends StatelessWidget{
  Widget build(BuildContext context){
    return Scaffold(
      //appBar:AppBar(title:Text("Rose-Bergine ROYAL,etudiante a l'ecole superieure Infotronique d'Haiti "))
      backgroundColor: Colors.lightBlueAccent,
       body: Center(
        child: Text(
          "Rose-Bergine ROYAL, etudiante a l'ecole superieure infotronique d'Haiti",
           style: TextStyle(
            fontSize: 18, // Taille du texte
            color: Colors.white,
            ),
          ),
          ),
    );
  }
}
