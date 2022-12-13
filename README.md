# OCR-Android

Simple ocr making using Google ML Kit for android


## How to use Google ML Kit for android

Gradle
```
implementation 'com.google.android.gms:play-services-mlkit-text-recognition:18.0.2'
implementation 'com.google.android.gms:play-services-vision:20.1.3'
```

Manifest
```
<meta-data
   android:name="com.google.mlkit.vision.DEPENDENCIES"
    android:value="ocr" />
```



## Demo
![](media/ocr.gif)

## Used libraries
- [Google ML Kit](https://developers.google.com/ml-kit)
- [PermissionX](https://github.com/guolindev/PermissionX)
- [ImagePicker](https://github.com/Dhaval2404/ImagePicker)
