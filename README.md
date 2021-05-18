### Restart app in Flutter!

------------

*A simple plugin to restart your flutter application WITH NATIVE APIs.*

------------
####How to use it?
------------
**1.  Add the package to pubspec.yaml dependency:**
```yaml
dependencies:
  restart: ^1.0.0
```
**2. Import package:**
```dart
import 'package:restart/restart.dart';
```
**3. Call the restartApp method where ever you want:**
```dart
onTap(){
	Restart.restartApp();
}
```