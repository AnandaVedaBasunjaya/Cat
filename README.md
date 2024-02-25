//Cat
//Cat android
import 'package:flutter/material.dart';

void main() {
  runApp(
      MaterialApp(
          debugShowCheckedModeBanner: false,
          home: Scaffold(
            backgroundColor: Colors.blueAccent,
            appBar: AppBar(
              title: Text('Catto', style: TextStyle(color: Colors.white, fontWeight: FontWeight.bold),),
              backgroundColor: Colors.grey,
              centerTitle: true,
            ),
            body: Center(
              child: Image(image: NetworkImage('https://ih0.redbubble.net/image.4789831581.5724/raf,360x360,075,t,fafafa:ca443f4786.jpg')),
            ),
          ),
          ),
      );
}
