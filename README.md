edurun

ionic cordova resources ios

cordova plugin save
cordova platform rm ios
cordova platform add ios

cordova emulate ios --list

cd platforms/ios/cordova && npm install ios-sim@latest

cd platforms/ios && pod install

cordova emulate ios --buildFlag='-UseModernBuildSystem=0' --target="iPhone-XR, 12.2"
