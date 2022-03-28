# sdp/ssp - Android scaled size units
An Android library that provides 2 new size units - sdp (scaled dp) and ssp (scaled sp).

Scaled dp and scaled sp are calculated based on a device whose screen width is 360dp. It means that 1 sdp or 1 ssp is respectively equal to 1 dp or 1 sp on a that device.

There are different predefined set of values those are interpolated for different screen widths, i.e 300dp, 33dp, 390dp...If the screen width of a specific device is not exactly equals to those predefined screen widths, the system will choose the closet set of values.

# Example
// TODO

# Getting Started

To add sdp to your project (Using Android Studio and Gradle): 
## Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:
  
  ```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
## Step 2. Add the dependency
  
  ```
	dependencies {
	        implementation 'com.github.duchuyctlk:sdp:main-SNAPSHOT'
	}
  ```

See the [dimens.xml](https://github.com/duchuyctlk/sdp/blob/main/sample/src/main/res/values/dimens.xml) to know how to use to the sdp and ssp size units.
