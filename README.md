# Quiz App

### Description

Quiz App is a quiz application designed to offer users an interactive way to test their knowledge in different subjects. 
With a focus on user experience, the app presents a clean and intuitive interface that guides users through a series of questions, immediate feedback on answers, and detailed statistics to track their progress over time.

## Key Challenges

### During the development of Quiz App, I had some problems: 

From type mismatches with Dart's Future and Map types, while using asynchronous data handling. Integrating Riverpod for state management was challenging due to the complexity of setting up providers and accessing shared data.
I was able to master it while using FutureBuilder for asynchronous and managing Future types. 
However, complications arose with the implementation testing, leading to a decision to discard the use of Riverpod due to its complexity and difficulty in testing. This resulted in significant time spent troubleshooting and adjusting the application's architecture and functionality. Rewriting the code twice and eventually giving up while even the generic practice option is not fully working anymore. 
I had lots of problems troubleshooting with null safety, which required explicit declaration of variables that can be null. 


### pubspec.yaml

#### dependencies:
  flutter:
    sdk: flutter
  dio: ^4.0.0
  go_router: ^10.1.2
  http: ^0.13.3
  shared_preferences: ^2.2.1
  provider: ^6.0.0
  flutter_riverpod: ^2.4.4
  cupertino_icons: ^1.0.2

#### dev_dependencies:
  flutter_test:
    sdk: flutter
  integration_test:
    sdk: flutter
  mockito: ^5.0.0
  build_runner: ^2.1.8
  nock: ^1.2.3

