# Hand-Detection
This is an Android application which uses Mediapipe to detect hands in a live stream from a phone camera.

In order to run the app, clone it.

```git
git clone https://github.com/yashk2000/Hand-Detection.git`
```

In order to run Mediapipe apps using gradle, we need to build an aar for the desired graph being used. Follow the steps metioned [here](https://github.com/google/mediapipe/blob/master/mediapipe/docs/android_archive_library.md) to build and aar. 
Once the aar is made, keep it in the libs folder, `app/src/main/libs/`.

Then open the app in android studio. To get the app running, android-ndk also needs to be setup. Once that is setup from the settings, menu the app can be built successfully.

The app uses the phone GPU to detect hands in real time with a good accuracy. 

Here is how the app looks in action:

<img src="https://user-images.githubusercontent.com/41234408/80405981-faccd080-88e0-11ea-9c65-5c93e9c2d595.jpg" heigth="500" width="300" />
<img src="https://user-images.githubusercontent.com/41234408/80406016-0cae7380-88e1-11ea-9fc1-d794fd4791b8.jpg" heigth="500" width="300" />
