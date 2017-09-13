# test

https://stackoverflow.com/questions/37093723/how-to-add-an-android-studio-project-to-github

https://git-scm.com/download/linux

https://gist.github.com/lopspower/6f62fe1492726d848d6d

https://blog.akquinet.de/2011/02/25/android-activities-and-tasks-series-%E2%80%93-activity%C2%A0attributes/

http://horribile.blogspot.in/2011/11/two-activities-on-screen-at-same-time.html

http://www.androidsolved.com/question/android/answer/5071275/can-i-use-activity-group-to-show-two-activities-at-the-same-time-in-android

FIREBASE TEST LAB ENABLE TEST API GOOGLE LINK:-
https://console.developers.google.com/apis/api/testing.googleapis.com/overview

Firebase App dependencies:-

com.google.firebase:firebase-core:11.2.2	Analytics
com.google.firebase:firebase-database:11.2.2	Realtime Database
com.google.firebase:firebase-storage:11.2.2	Storage
com.google.firebase:firebase-crash:11.2.2	Crash Reporting
com.google.firebase:firebase-auth:11.2.2	Authentication
com.google.firebase:firebase-messaging:11.2.2	Cloud Messaging
com.google.firebase:firebase-config:11.2.2	Remote Config
com.google.firebase:firebase-invites:11.2.2	Invites and Dynamic Links
com.google.firebase:firebase-ads:11.2.2	AdMob
com.google.firebase:firebase-appindexing:11.2.2	App Indexing
com.google.firebase:firebase-perf:11.2.2	Performance Monitoring

apk decompiler site:-

http://www.javadecompilers.com/

https://physics.stackexchange.com/questions/196136/why-does-a-free-falling-body-experience-no-force-despite-accelerating


IONIC 2 CORDOVA MISSING ANDROID HOME ISSUE FIXED:-

vishal@vishal-HP-EliteBook-8560p:~/IONICAPPS/TestApp$ cordova run android --verbose
No scripts found for hook "before_run".
No scripts found for hook "before_prepare".
Checking config.xml and package.json for saved platforms that haven't been added to the project
Config.xml and package.json platforms are the same. No pkg.json modification.
Package.json and config.xml platforms are different. Updating config.xml with most current list of platforms.
PlatformApi successfully found for platform android
Checking config.xml for saved plugins that haven't been added to the project
Checking for any plugins added to the project that have not been installed in android platform
No differences found between plugins added to project and installed in android platform. Continuing...
Generating platform-specific config.xml from defaults for android at /home/vishal/IONICAPPS/TestApp/platforms/android/res/xml/config.xml
Merging project's config.xml into platform-specific android config.xml
Merging and updating files from [www, platforms/android/platform_www] to platforms/android/assets/www
Wrote out android application name "MyApp" to /home/vishal/IONICAPPS/TestApp/platforms/android/res/values/strings.xml
android-versionCode not found in config.xml. Generating a code based on version in config.xml (0.0.1): 1
Wrote out Android package name "io.ionic.starter" to /home/vishal/IONICAPPS/TestApp/platforms/android/src/io/ionic/starter/MainActivity.java
Updating icons at platforms/android/res
Updating splash screens at platforms/android/res
This app does not have additional resource files defined
Prepared android project successfully
No scripts found for hook "after_prepare".
ANDROID_HOME=/home/vishal/Desktop/Sdk/Sdk
JAVA_HOME=/usr/lib/jvm/java-8-oracle
Subproject Path: CordovaLib
Running command: /home/vishal/IONICAPPS/TestApp/platforms/android/gradlew cdvBuildDebug -b /home/vishal/IONICAPPS/TestApp/platforms/android/build.gradle -Dorg.gradle.daemon=true -Dorg.gradle.jvmargs=-Xmx2048m -Pandroid.useDeprecatedNdk=true
Error: spawn EACCES

vishal@vishal-HP-EliteBook-8560p:~/IONICAPPS/TestApp$ sudo chmod -R 777 /home/vishal/IONICAPPS/TestApp/platforms/android/gradlew

vishal@vishal-HP-EliteBook-8560p:~/IONICAPPS/TestApp$ cordova build android
ANDROID_HOME=/home/vishal/Desktop/Sdk/Sdk
JAVA_HOME=/usr/lib/jvm/java-8-oracle
Subproject Path: CordovaLib
Starting a Gradle Daemon, 1 busy Daemon could not be reused, use --status for details
The Task.leftShift(Closure) method has been deprecated and is scheduled to be removed in Gradle 5.0. Please use Task.doLast(Action) instead.


IONIC 2 GOOGLE MAP INTEGRATION:-
https://ampersandacademy.com/tutorials/ionic-framework-version-2/google-map-api-working-example
