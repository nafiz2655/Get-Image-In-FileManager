implement Library
 //image crop library
    implementation 'com.theartofdev.edmodo:android-image-cropper:2.8.+'

//gradel.propertise
    android.enableJetifier=true
//gradel.setting
    dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        jcenter() //this line add
        mavenCentral()
    }
}

//android manifest add
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<!--    camera permission-->
    <uses-permission android:name="android.permission.CAMERA" />
//and add

</application
--------------------
-------------
------------->

  <activity
            android:name="com.theartofdev.edmodo.cropper.CropImageActivity"
            android:theme="@style/AppTheme" />

    </application>

