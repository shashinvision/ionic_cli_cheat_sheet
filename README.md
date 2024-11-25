# ionic_cli_cheat_sheet

## Getting Started
- Create a new Ionic project
```bash
ionic start myApp 
 ```
- Start the development server
 ```bash
ionic serve
```
## Project Management
 - Build the app for production
```bash
ionic build
```
- Run the app in a lab environment
```bash
ionic lab
```
- Prepare the app for Capacitor
```bash
ionic capacitor prepare 
```
or 
- Prepare the app for Cordova
```bash
ionic cordova prepare 
```

## Platform Management with capacitor
- Add the Android platform
```bash
ionic capacitor add android
```
- Add the iOS platform
```bash
ionic capacitor add ios
```
- Remove the Android platform
```bash
ionic capacitor rm android
```
- Remove the iOS platform
```bash
ionic capacitor rm ios
```

## Platform Management with cordova
- Add the Android platform
```bash
ionic cordova platform add android
```
- Add the iOS platform
```bash
ionic cordova platform add ios
```
- Remove the Android platform
```bash
ionic cordova platform rm android
```
- Remove the iOS platform
```bash
ionic cordova platform rm ios
```

## Emulation and Simulation with capacitor
- Emulate the app on an Android device
```bash
ionic capacitor emulate android 
```
- Emulate the app on an iOS device
```bash
ionic capacitor emulate ios 
```
- Run the app on a connected Android device
```bash
ionic capacitor run android 
```
- Run the app on a connected iOS device
```bash
ionic capacitor run ios 
```

## Emulation and Simulation with cordova
- Emulate the app on an Android device
```bash
ionic cordova emulate android 
```
- Emulate the app on an iOS device
```bash
ionic cordova emulate ios 
```
- Run the app on a connected Android device
```bash
ionic cordova run android 
```
- Run the app on a connected iOS device
```bash
ionic cordova run ios 
```

## You can also include other commands specific to your project, such as custom scripts or plugins.

### Generate Commands
- Generate a module
```bash
ionic generate module myModule  
```
- Generate a module with routing 
```bash
ionic generate module myModule --routing
```
- Generate a new component without test file
```bash
ionic generate component myComponent --spec=false
```
- Generate a new component
```bash
ionic generate component myComponent 
```
- Generate a new page
```bash
ionic generate page myPage 
```
- Generate a new directive
```bash
ionic generate directive myDirective 
```
- Generate a new pipe
```bash
ionic generate pipe myPipe 
```
- Generate a new provider
```bash
ionic generate provider myProvider 
```
- Generate a new service
```bash
ionic generate service myService 
```
- Generate a new tab layout
```bash
ionic generate tabs 
```
- Generate a new sidemenu layout
```bash
ionic generate sidemenu 
```

## Other Commands
- Display information about the project
```bash
ionic info 
```
- Check the project for errors and provide fixes
```bash
ionic doctor
```
