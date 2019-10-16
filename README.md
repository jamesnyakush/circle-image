# circle-image

[![](https://jitpack.io/v/jamesnyakush/MaterialUI.svg)](https://jitpack.io/#jamesnyakush/MaterialUI)


<img src="https://github.com/jamesnyakush/MaterialUI/blob/master/photos/otp.png" width="280"/> 

This a collection of material ui with otp custom view


## Download

Add jitpack to project level build.gradle

```groovy
allprojects {
 repositories {
    maven { url "https://jitpack.io" }
 }
}
```

Then add the library to module level build.gradle.
```groovy
 implementation 'com.github.jamesnyakush:MaterialUI:Tag'
```

## Usage

Add OTPEditText to your layout to get started.

```xml
        <com.jamesnyakush.otp.OTPEditText
            android:id="@+id/etxt_four"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:layout_gravity="center"
            android:layout_marginLeft="15dp"
            android:background="@drawable/circle"
            android:gravity="center"
            android:hint="0"
            android:inputType="number"
            android:maxLength="1"
            android:textCursorDrawable="@color/black"/>
``` 


<i>&copy; jamesnyakush</i>
