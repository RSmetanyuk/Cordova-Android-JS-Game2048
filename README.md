This is my first hybrid mobile application built by PHONEGAP/CORDOVA with HTML, CSS, and JavaScript .

It is the popular game 2048, which HTML, CSS, and JavaScript code I took from here https://code.sololearn.com/WYWMDCa664ex#html

![Mobile game 2048](https://drive.google.com/open?id=1QVvN2Iir4cwJyR89CxnLgMq9d-GVBD7m)

HOW TO START THIS APP ON PHONE

First, install the Cordova command-line utility by running the following command:
sudo npm install -g cordova

In your local folder create a new Cordova project by running the following command, where [your-app-name] is the folder where the app will be created:
cordova create your-app-name com.example.myapp MyAppName

Add the desired platforms such as ios, android, windows, wp8, blackberry10, firefoxos, amazon-fireos. I use android:
cordova platform add android	

In your created local project folder, you should find the "www" directory. This is where your web app is located. Replace all files in this local directory by files from such named folder “www” at this repository.

Connect your android phone to mac by cable, and Enable on phone USB Debugging.

Open command line in the project folder and run command:
cordova run android --device

That's all. App will be installed on your phone.


Also, you need to have installed on your mac:
Java Development Kit (JDK) 8.
Android Studio.
