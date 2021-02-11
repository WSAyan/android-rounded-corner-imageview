# RoundedCornerImageView

[![](https://jitpack.io/v/WSAyan/android-rounded-corner-imageview.svg)](https://jitpack.io/#WSAyan/android-rounded-corner-imageview)

ছবির কোনা হালকা গোল করার ব্যথা থেকে মুক্তি দেয়

Make imageview corner rounded easily.

## Usage

Step 1. Add the JitPack repository to your build file

```Groovy
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

Step 2. Add the dependency


```Groovy
dependencies {
	        implementation 'com.github.WSAyan:android-rounded-corner-imageview:v1-1.0.0'
	}
```

Step 3. Set `cornerRadius` if you want otherwise it just acts as normal ImageView.

```xml
<com.wsayan.roundedcornerimageview.RoundedCornerImageView
        android:layout_width="300dp"
        android:layout_height="300dp"
        android:src="@drawable/your_image"
        app:cornerRadius="10dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
```
