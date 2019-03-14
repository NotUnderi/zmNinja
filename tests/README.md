Appium install: http://appium.io/docs/en/about-appium/getting-started/
Python Appium client install: https://github.com/appium/python-client


Android
---------
I currently test on an Android 7.1.1 emulator. Change test.py config as needed

./startappium.sh


iOS
----
Read/follow: http://appium.io/docs/en/drivers/ios-xcuitest/index.html
https://github.com/appium/appium-xcuitest-driver

For iOS: Also needs 

```
brew install carthage 
brew tap wix/brew && brew install wix/brew/applesimutils
```

Just run appium (not start-appium.sh)
export USE_PORT=8100 (maybe)

To run test cases,
```
cd testcases
python ./test.py --ios OR --android