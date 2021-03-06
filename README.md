# maven
Maven repository for our open-source projects on github.

Usage
=======

To use our libraries, just add our repo as a new maven repository in the top-level build.gradle of your project :

```javascript
allprojects {
    repositories {
        mavenCentral()
        maven {
            url 'https://github.com/netcosports/maven/raw/master/'
        }
        ...
    }
}
```

After that, you will be able to add dependency on any project listed bellow.

RecyclerGesture
=======

A light weight library used to easily attached simple gesture to recycle view based on RecyclerView.addOnItemTouchListener().

Add the following lines to the build.gradle of your module : 

Stable version
```javascript
dependencies {
    ...
    compile 'com.netcosports.recyclergesture:library:0.1.0@aar'
    ...
}
```

Snapshot
```javascript
dependencies {
    ...
    compile 'com.netcosports.recyclergesture:library:0.2.0@aar'
    ...
}
```

More information : [RecyclerGesture on GitHub](https://github.com/netcosports/RecyclerGesture)

CircleIndicator
=======

A lightweight viewpager indicator such as the nexus 5 launcher indicator.

```javascript
dependencies {
    ...
    compile 'com.netcosports.circleindicator:library:1.1.8@aar'
    ...
}
```

More information : [CircleIndicator on GitHub](https://github.com/netcosports/CircleIndicator/)
