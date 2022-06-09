# nums-api-m

NumbersAPI mobile is a cross-platform smartphone application built with react-native-app using Ionic.
Gets data from [NumbersAPI](http://numbersapi.com/) API.

Fetches data from four different categories: Math, Trivia, Date, Year. 

Home page has documentation about the functionality of the NumbersAPI webpage API.

Select category from nav bar at the bottom of the screen.
Each category can either generate a random fact or a fact based on the numeric input. 
  - If the input field is empty, button will generate a random fact. 
  - If the input field has a number it will generate a specific fact.
  - non numeric input will throw an error.

## Setting Up Dev Environment

### Create React Native App

Create React Native App was used for the development environment. If you have issue setting up with Expo CLI or React Native CLI, [Create React Native App](https://reactnative.dev/blog/2017/03/13/introducing-create-react-native-app) is recommended. 


### Ionic

Built using [Ionic's](https://ionicframework.com/getting-started#install) component based framework. 


### Running the application

To run the application in your browser 
```
ionic serve
```

To run in a simulator

ios:
``` 
ionic capacitor run ios
```

andriod:
```
ionic capacitor run android
```
