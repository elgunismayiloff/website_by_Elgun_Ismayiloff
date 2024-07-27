
Here’s the translated README.md file in English, reflecting the latest updates:

---

# Jasperpack

`Jasperpack` is a Flutter package offering various animation loaders with color transitions and nested animations.



## Features

- **JasperLoader**: A rotating loader animation with color transitions.
- **JasperLoader2**: Nested rotating loader animations with multiple color animations.

## Installation

To add `jasperpack` to your project, include it in the `dependencies` section of your `pubspec.yaml` file:

```yaml
dependencies:
  jasperpack:
    ^1.0.0 # Use the latest version available
```

Then, run the following command in your terminal to install the package:

```sh
flutter pub get
```

## Usage

### JasperLoader

`JasperLoader` displays a loader animation that rotates through a list of colors. Here’s a basic usage example:

```dart
import 'package:flutter/material.dart';
import 'package:jasperpack/color_loader.dart'; // Import the package

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      title: 'Jasperpack Example',
      theme: ThemeData(
        primarySwatch: Colors.blue,
      ),
      home: MyHomePage(),
    );
  }
}

class MyHomePage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text('Jasperpack Example'),
      ),
      body: Center(
        child: JasperLoader(
          colors: [Colors.red, Colors.green, Colors.blue],
          duration: Duration(seconds: 1),
        ),
      ),
    );
  }
}
```

### JasperLoader2

`JasperLoader2` Here’s how to use it:

```dart
        JasperLoader2(dotOneColor: Colors.pink,  
        dotTwoColor: Colors.amber,  
        dotThreeColor: Colors.deepOrange,  
        dotType: DotType.square,  
        duration: Duration(seconds: 2)),
```

### JasperLoader3

`JasperLoader3` Here’s how to use it:

```dart
        JasperLoader3(  
        color1: Colors.deepOrangeAccent,  
        color2: Colors.yellow,  
        color3: Colors.lightBlue),
```

### JasperLoader5

`JasperLoader5` Here’s how to use it:

```dart
        JasperLoader5(dotOneColor: Colors.pink,  
        dotTwoColor: Colors.amber,  
        dotThreeColor: Colors.deepOrange,  
        dotType: DotType.circle,  
        dotIcon: Icon(Icons.adjust),  
        duration: Duration(seconds: 1)),
```

## Contributing

If you’d like to contribute, please follow these steps:

1. **Fork**: Fork the repository to your own GitHub account.
2. **Branch**: Create a new branch for your changes.
3. **Commit**: Commit your changes.
4. **Pull Request**: Submit a pull request on GitHub.

Thank you for your contributions!

---

Feel free to adjust any sections based on your specific needs or additional information you might want to include.
# website_by_Elgun_Ismayiloff

by Elgün İsmayıloff Köməklik lazım olarsa

#instagram: @elgunismayiloff
