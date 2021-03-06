# Avathor-Android-Library
Avatar images for the Bitcoin Lightning network!

This is an implementation of the [Avathor specification](https://github.com/michaelWuensch/avathor-rfc) for android.

## Usage
Add the following dependency to your root build.gradle file.

```
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```

Add the following dependency to your build.gradle file.

```
dependencies {
	implementation 'com.github.michaelWuensch:avathor-android-library:1.1.0'
}
```

After that, all you have to do is:
```

Bitmap avathor = AvathorFactory.getAvathor(Context, String);

```

## Licenses & Attribution

The licenses and attribution for the artwork follows below.
If you use any of the images from the assets folder for your own projects, make sure to give proper attribution.

- The "robots" artwork and the some of the backgrounds (abstract_01 & travel_01) were created by Zikri Kader.<br> 
They are available under CC-BY-3.0 or CC-BY-4.0 license.

- The "aliens" artwork was created by Hrvoje Novakovic.<br>
They are available under CC-BY-3.0 license.

- The "animals" (cats & birds) artwork was created by David Revoy. <br>
They are available under CC-BY-4.0 license.<br> 
https://www.peppercarrot.com/en/article391/cat-avatar-generator

- The "humans" artwork was created by Pablo Stanley, for https://avataaars.com/.<br>
They are "Free for personal and commercial use."

- The backgrounds abstract_02 and travel_02 are images taken from various artists from pixabay.com (CC0) which were adapted and optimized by Johannes Wuensch.
