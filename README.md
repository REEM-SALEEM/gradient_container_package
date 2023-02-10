splash_container
splash_container package lets you add a beautiful gradient container to your Flutter app.

Installation
Add the latest version of package to your pubspec.yaml (and rundart pub get):
dependencies:
  splash_container: ^0.0.1
Import the package and use it in your Flutter App.
import 'package:fancy_containers/splash_container.dart';
Example
There are a number of properties that you can modify:

height
width
title
subtitle
gradient (color1 and color2)
class GradientContainerScreen extends StatelessWidget {  
  const GradientContainerScreen({Key? key}) : super(key: key);  
  
  @override  
  Widget build(BuildContext context) {  
    return Scaffold(  
      body: Center(  
        child: const GradientContainer(  
          title: 'Hello World',  
          color1: Colors.lightGreenAccent,  
          color2: Colors.lightBlue,  
          subtitle: 'This is a new package',  
        ),  
      ),  
    );  
  }  
}