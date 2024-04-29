# Random Country

This Flutter app retrieves and displays details of a random country using the [RESTCountries API](https://restcountries.com/).

Built in the context of the article [_I built the same app with Flutter, React Native, and Ionic_
](https://medium.com/@fmmagalhaes/i-built-the-same-app-with-flutter-react-native-and-ionic-33ff8b358562)

## Test
https://fmmagalhaes.github.io/random_country_flutter

## Run
`flutter run`

<img src="https://github.com/fmmagalhaes/random_country_flutter/assets/8866496/ba22e50f-9273-40c7-8eff-b088269d90b1" width="300">

## Deploy to GitHub Pages
1. `flutter config --enable-web`
2. `flutter create .`
3. `flutter build web --base-href=/random_country_flutter/`
4. Create a branch called `gh-pages` with the content of the `build/web` folder.
