# API_Security
//manifest
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">
<!-- Use Permission   -->
    <uses-permission android:name="android.permission.INTERNET"/>
    <uses-permission android:name="android.permission.ACCESS_WIFI_STATE"/>
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE"/>

    <application
        android:allowBackup="true"
      
        tools:targetApi="31">

  //=========================================================================      

//build:gradle(app)

  buildTypes {
        release {
            // minifyEnabled and  shrinkResources true
            minifyEnabled true
            shrinkResources true
           
        }
    }

dependencies {

    implementation libs.appcompat
 
    //   volley implement
    implementation libs.volley
}