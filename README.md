# Camera
Camera Using CameraX Api

/*-----------------------------Dependencies------------------------------------*/
implementation 'androidx.appcompat:appcompat:1.1.0-alpha03'
implementation 'androidx.constraintlayout:constraintlayout:1.1.3'
def cameraxVersion = "1.0.0-alpha02"
implementation "androidx.camera:camera-core:${cameraxVersion}"
implementation "androidx.camera:camera-camera2:${cameraxVersion}"


/*-----------------------------User Permission-----------------------------------*/
<uses-permission android:name="android.permission.CAMERA" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>

/*-----------------------------------App Configuration---------------------------*/
    defaultConfig {
        applicationId "com.alok.camera"
        minSdkVersion 30
        targetSdkVersion 30
        versionCode 1
        versionName "1.0"

        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"
    }
