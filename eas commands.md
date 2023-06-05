## Create a new application
npx create-expo-app name

## Check Output on Expo Go app
npx expo start or npx expo start --tunnel

## To stop the server playing the output
Ctrl + C to stop the server/output


## Check output on expo go app

## To create a build install eas cli 
npm install -g eas-cli

## Login with expo account
eas login
enter login details

## To create eas.json file
- npx cross-env EAS_NO_VCS=1 eas build:configure


## Change eas.json file
"preview": {
      "distribution": "internal",


      "android":{
        "buildType": "apk"
      },


      "ios": {
        "resourceClass": "m-medium"
      }
    },


## Using the build command
npx cross-env EAS_NO_VCS=1 eas build -p android --profile preview


com.example.app
com.raveen.one