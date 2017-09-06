# Android Studio Installation


## Why Android development?

There are over 1 billion android devices active and 2.2 millions android apps on play store today. Android represents an incredible opportunity for developers. Android apps can be developed on both Android Studio and Eclipse. Android Studio is the official IDE for Android app development by Google and contains many tools which are quite helpful to developers, and provides a seamless integration with the rest of the Google Developer Suite. So, it is highly recommended to use Android Studio over Eclipse.

## Quick Overview

An android app is written in XML for the frontend UI and JAVA for the backend.

All the backend part is done using Java. But now, Kotlin Language is declared for Official by Google for Android development.Although it’s not a big deal to switch to Kotlin as If you know any object oriented programming language, then it will not be much difficult to relate to the concepts used during development. In short if you know C++ then also you are at peace.

The frontend part is done using XML. All user interface elements in an Android app are built using View and ViewGroup objects. 

## Installation of Android Studio

JDK and JRE are essential for JAVA to run on your machine.

### For Linux Users :

#### Installing JAVA : 

Open up your Terminal ( Alt + Shift + T) and follow the below commands to install JDK and JRE.

### Step 1: Update package list

`sudo apt-get update`

### Step 2: Install JRE and JDK

`sudo apt-get install default-jre  default-jdk  oracle-java8-installer`

### Step 3: Configure Java

`sudo update-alternatives --config java`

### Step 4: Set environment variable replacing YOUR_PATH with path which last command returned

`sudo vim /etc/environment – add JAVA_HOME="YOUR_PATH"`

### Step 5:

`source /etc/environment`


Visit this [link](https://www.digitalocean.com/community/tutorials/how-to-install-java-on-ubuntu-with-apt-get) for any reference.

## Installing IDE

1. Follow this [link](https://developer.android.com/studio/index.html) and select all the packages for linux. This will download the zip file.

2. Extract the file.

3. In terminal type: 
`cd /{Location where you extracted the zip file}/android-studio/bin` and then `sh studio.sh`

This will open up the android studio. Somewhat similar to below would appear. Select configure in it.

![start](images/start.png)

Click on the SDK Manager icon 

![configure](images/configure.png)

Now the below window will appear. Install the ticked packages shown in the below image.

![sdk-tools](images/sdk-tools.png)

Select the below checked boxes to install the Android Software Development Kit for different versions of Android. If you can't see the individual packages, tick the check-box in the bottom right corner titled "Show Package Details".

![sdk](images/sdk.png)










