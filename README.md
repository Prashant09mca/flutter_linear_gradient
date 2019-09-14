# linear_gradient

A Flutter plugin for iOS and Android for Linear gradient with 300+ different color combination.

> Feedback and Pull Requests are most welcome!

## Installation

Add to pubspec.yaml.

```yaml
dependencies:
  ...
  linear_gradient: ^0.1.2
```

### How to use.

import custom_gradient.dart

```dart
import 'package:linear_gradient/linear_gradient.dart';
```

## Usage Example.

```dart
import 'package:flutter/material.dart';
import 'package:linear_gradient/linear_gradient.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  /// This is an example app which make use of
  /// How to use `Custom Gradient Box Decoration`

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Container(
        decoration: BoxDecoration(
            gradient: LinearGradientStyle.linearGradient(
                orientation: LinearGradientStyle.ORIENTATION_HORIZONTAL,
                gradientType: LinearGradientStyle.GRADIENT_TYPE_AMIN)),
      ),
    );
  }
}

```

# Video
- <a href="https://www.youtube.com/watch?v=Ig6Khy9LHX8">Watch Video</a>

### Gradient Orientation.

CustomGradient.ORIENTATION_HORIZONTAL.
CustomGradient.ORIENTATION_VERTICAL.


### Gradient Type (300+ Type are available).
Here is Some Examples.

CustomGradient.GRADIENT_TYPE_GRADE_GREY.
CustomGradient.GRADIENT_TYPE_PIGGY_PINK.
CustomGradient.GRADIENT_TYPE_COOL_BLUES.
CustomGradient.GRADIENT_TYPE_MEGATRON.
CustomGradient.GRADIENT_TYPE_MOONLIT_ASTEROID.
CustomGradient.GRADIENT_TYPE_JSHINE.
CustomGradient.GRADIENT_TYPE_EVENING_SUNSHINE.
CustomGradient.GRADIENT_TYPE_DARK_OCEAN.
CustomGradient.GRADIENT_TYPE_COOL_SKY.
CustomGradient.GRADIENT_TYPE_YODA.
CustomGradient.GRADIENT_TYPE_MEMARIANI.

# ☕️ Buy Coffee
 <a href="https://www.buymeacoffee.com/technoprashant" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
