[![](https://getmcss.com/_nuxt/img/logo.bdd3922.svg)](https://www.getmcss.com)

# OVERVIEW
MCSS (Mobile Cascade Style Sheet) is a new low code technology to speed up the development of native mobile apps. MCSS describes how the views and the different components are to be displayed on the mobile devices. MCSS saves a lot of work and time, it can control the layout of multiple views all at once and simultaneously in Android and IOS.

MCSS is not a hybrid technology, applications developed using MCSS continue being 100% native. You can use your favorite IDE, XCode, Android Studio, Eclipse, and more by installing this powerful library in your project ([how to install MCSS on your application project](https://docs.getmcss.com/installation-android)), your app will apply the design described in the .mcss files.

Once you create a .mcss file, that can be stored either on an external URL or locally in your project, the library will apply the instructions natively (JAVA/Swift) of your .mcss file to the different views and objects. Just like CSS works on an HTML website. ([Read about the properties and components supported by MCSS](https://docs.getmcss.com/selectors)).

# WHY MCSS?

- Reduce native mobile app development by more than 40%.

- Can create complex designs and replicate them an infinite amount of times by just one line of code.

- No need to be an expert mobile developer to create a great looking app.

- Easy to maintain and update the app across the codebase and app store on iOS and Android.

- Helps provide the same design and aesthetics for iOS and Android version.

### Just like CSS is in HTML, MCSS has been to Swift for iOS and Java for Android.

- MCSS Provide developers with a way to connect the objects in each view of a mobile app with a set of stylesheets controlled by rules to edit and manage the design of the entire application simultaneously in Android and IOS.

- Having the MCSS File (Stylesheet) stored in an external URL, developers can update the design and aesthetics of views and objects in the Android and IOS applications that are in production skipping the process of submitting new versions to the app stores. Any aesthetic and design changes will be available to end users in almost real time (next time they go back to the application)

# HOW TO INSTALL

### Gradle Package Manager:

1.  Open the project's settings.gradle file in your Android Studio project and add the following code fragment:

		dependencyResolutionManagement {
			repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
			repositories {
        			...
				maven { url 'https://jitpack.io' }
			}
		}

2.  Open the module's build.gradle file, add the following code fragment:

		dependencies {
			implementation 'com.github.getmcss:MCSS-FRAMEWORK-ANDROID:1.0.1'
		}


### Manual installation:

1.  Download the mcss-android-release.aar framework from the https://github.com/getmcss/MCSS-FRAMEWORK-ANDROID if your project uses Android

    ```
    git clone https://github.com/getmcss/MCSS-FRAMEWORK-ANDROID 
    ```

2.  In the main module of your Android Studio project verify that the libs folder exists.

3.	Copy the mcss-android-release.aar framework you just downloaded into the libs folder.

4.	Open the module's build.gradle file, add the following code fragment:

		dependencies {
			implementation files('libs/mcss-android-release.aar')
		}  

# COPYRIGHT & LICENSE
© 2022 MCSS | getmcss.com | Do Genius On. All rights reserved | Patent pending 

[MCSS License](https://www.getmcss.com/end-user-license).
