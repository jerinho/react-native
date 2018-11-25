# scaffolding codebase for react native
react native version : 0.55.4
for WINDOWS only. other platforms will be supported soon
as for now this is for ANDROID only
for native react native 's installation only. expo based project not supported
let me know if there exists any later versions of react native with the same stability and maturity you found somewhere. thank you

# requirement
1. windows
2. elevated privilege console (cmd)
3. nodejs + npm
4. yarn (installed using "npm install yarn")
5. react-native (installed using "npm install react-native")

# installation
1. copy this repo to a local working directory
2. edit android/local.properties. point to your android SDK location 
3. go to working directory from console
4. run these by order
> yarn
> cd android
> gradlew.bat installDebug

# project run
1. connect device or run android simulator
2. go to working directory from console
3. run > react-native run-android
4. expected : metro bundler console window is running and app is running showing a greeting message
5. if not, don't hesitate to add your issue here
