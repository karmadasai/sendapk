# sendapk - Install and Start APK remotely

Connect to device via ADB

    adb connect <ip:port>

Install the APK to the device

    adb -s <ip:port> install -r <app.apk>

Send Powerbutton keyevent to device

    adb -s <ip:port> shell input keyevent 26

Start the App

    adb -s <ip:port> shell monkey -p <package name> -c android.intent.category.LAUNCHER 1

