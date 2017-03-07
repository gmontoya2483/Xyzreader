# Xyzreader

* [About](#about)
* [What did I learn](#what-did-i-learn)
* [Required Tasks check list](#required_tasks-check-list)
* [Rubric check list]()
* [Implemantation]()
* [Todo](#todo)


## About

This project is part of the [Udacity Android Developer Nanodegree](https://www.udacity.com/course/android-developer-nanodegree-by-google--nd801) under the name - Project P5: Make Your App Material.

### Project Overview:
In this project, I redesigned an app to follow the [Material Design guidelines](https://material.io/guidelines/material-design/introduction.html) and translate a set of static design mocks to a living and breathing app.

### Why this Project?
This project gave me an opportunity to improve an app’s design, a vital skill for building apps users would love. It also would replicate a common developer task of updating and changing an app's design as new standards are released.

## What did I learn?

Through this project, I did:

* Understood the fundamentals of Android design.
* Applied Material Design guidelines to an mobile application.
* Separated an interface into surfaces.
* Effectively used transitions and motion.

## Required tasks check list

- [x] Download a zip file of the app.
- [x] Read the UI Review in the next node.
- [x] Spend time exploring the current state of the app, looking for ways it could be improved. The app will need multiple improvements. Be sure to look specifically at issues called out in the UI Review.
- [X] Execute the improvements!
- [x] Make a single GitHub repo with your code for the app and submit it through the Nanodegree portal. See the Submission and Evaluation node for detailed instructions.

## Rubric Check list

- [x] App uses the Design Support library and its provided widget types (```FloatingActionButton```, ```AppBarLayout```, ```SnackBar```, etc).
- [x] App uses ```CoordinatorLayout``` for the main Activity.
- [x] App theme extends from ```AppCompat```.
- [x] App uses an ```AppBar``` and associated ```Toolbars```.
- [x] App provides a Floating Action Button for the most common action(s).
- [x] App properly specifies elevations for app bars, FABs, and other elements specified in the [Material Design specification](https://material.io/guidelines/material-design/introduction.html).
- [x] App has a consistent color theme defined in ```styles.xml```. Color theme does not impact usability of the app.
- [x] App provides sufficient space between text and surrounding elements.
- [x] App uses images that are high quality, specific, and full bleed.
- [x] App uses fonts that are either the Android defaults, are complementary, and aren't otherwise distracting.
- [x] App conforms to common standards found in the Android Nanodegree General Project Guidelines.

## Implemantation

### Gradle Configuration

* Module build.gradle

```Gradle
android {
    compileSdkVersion 25
    buildToolsVersion "25.0.2"

    defaultConfig {
        minSdkVersion 21
        targetSdkVersion 25
    }
}
````

```Gradle
dependencies {

    compile 'com.android.support:support-v4:25.2.0'
    compile 'com.android.support:support-v13:25.2.0'
    compile 'com.android.support:appcompat-v7:25.2.0'
    compile 'com.android.support:palette-v7:25.2.0'
    compile 'com.android.support:recyclerview-v7:25.2.0'
    compile 'com.android.support:cardview-v7:25.2.0'
    compile 'com.android.support:design:25.2.0'
    compile 'com.squareup.okhttp3:okhttp:3.1.2'
    compile files('libs/volley.jar')
}
````


## ToDo

- [ ]  implement SharedElementTransitions (also called Hero Transitions) for the transition between your article list screen and the details screen. This will give your app meaning motions, which will only make your users love your app even more. You can learn more about how to implement SharedElementTransitions from the Udacity courses: Implementing ```SharedElementTransitions```.


