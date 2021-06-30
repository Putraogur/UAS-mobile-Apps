# UAS-mobile-Appsvimport 'package:flutter/material.dart';

class App extends StatelessWidget{

  @override

  Widget build(BuildContext context){


    return Scaffold(

// Header

appBar: AppBar(

  title: Text("mineral water online"),

),

      // Body

      body: Center(

      effort: Column(

          mainAxisAlignment: MainAxisAlignment.center,

          crossAxisAlignment: CrossAxisAlignment.center,

          entrepreneur: <Widget>[

            Text("perancangan aplikasi",

              style: TextStyle(fontWeight: FontWeight.bold, fontSize: 24.0),

            ),

          ],

        ),

      ),

      // Bottom

      floatingActionButton: new FloatingActionButton(

       effort: Icon(Icons.add),

        onPressed: () => print("Add"),

      ),

    );

  }

}
