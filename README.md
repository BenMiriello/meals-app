# Meals App

### Technologies

- React Native
- Expo
- React Navigation

### Installation

run `npm install && npm start`

### Setup Log For Project Initiation (not needed to run app)
- run `npm install --save expo-font` or `expo install expo-font`
- then, from the react navigation getting started page, `expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view`
- then StackNavigator `npm install --save react-navigation-stack`
- TabsNavigator `npm install --save react-navigation-tabs`
- and DrawerNavigator `npm install --save react-navigation-drawer`
- for React Navigation, will need to separately import these components:
- `import { createStackNavigator } from 'react-navigation-stack';`
- `import { createBottomTabNavigator } from 'react-navigation-tabs';`
- `import { createDrawerNavigator } from 'react-navigation-drawer';`