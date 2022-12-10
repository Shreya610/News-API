## Usage
1. Please open file **constant_config.dart** and change `YOUR API KEY` in the variable `keyNewsApi` with your own.
2. In development mode, I'm used fake json server. So, the data is not realtime. 
3. Build flavor only work for Android. So, if you want to run as development mode you can use this command.
```
flutter run -t lib/main_development.dart --flavor development -d <device_id>
```
or in production mode.
```
flutter run --release -t lib/main_production.dart --flavor production -d <device_id>
```
*Note: If you want to build and release this app to Play Store. Please use this command.*
```
flutter build appbundle --release --flavor production -t lib/main_production.dart
```
4. For iOS, you can use this command as development mode.
```
flutter run -t lib/main_development.dart -d <device_id>
```
or in production mode.
```
flutter run --release -t lib/main_production.dart -d <device_id>
```
For iOS, to build and release there is no configuration. Just follow the instructions from the [documentation](https://flutter.dev/docs/deployment/ios).

