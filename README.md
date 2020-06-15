<a href="https://bluzelle.com/">
    <img src='https://raw.githubusercontent.com/bluzelle/api/master/source/images/Bluzelle%20-%20Logo%20-%20Big%20-%20Colour.png' alt="Bluzelle" style="width: 100%"/>
</a>


# Bluzelle Android

<img src="docs/exampleLogin.png" width="240" heigh="400">    <img src="docs/exampleMain.png" width="240" heigh="400">


## Install IDE

Follow instructions to install the latest [Android Studio](https://developer.android.com/studio/install).


## Start project

Use one of the following two options to start a new project.

### Option 1

Open Android Studio. Select 'Get from Version Control'.

<img src="docs/getFromVersionControl.png" width="683" heigh="384">

Or select **File** > **New** > **Project from Version Control...**.

Enter URL 'https://github.com/aqoleg/blzandroid.git'.

<img src="docs/enterUrl.png" width="683" heigh="384">

Open.

<img src="docs/checkoutOpen.png" width="683" heigh="384">

Wait for the project to be imported and updated.

<img src="docs/waitUpdated.png" width="683" heigh="384">

### Option 2

Get the package from github.

    $ git clone https://github.com/aqoleg/blzandroid.git

Open Android Studio. Select 'Import project'.

<img src="docs/importProject.png" width="683" heigh="384">

Or select **File** > **New** > **Import Project...**.

Select the root of the package.

<img src="docs/selectRoot.png" width="683" heigh="384">

Wait for the project to be imported and updated.

<img src="docs/waitUpdated.png" width="683" heigh="384">


## Build

Build debug or release APK.

### Debug

Select **Build** > **Build Bundle(s) / APK(s)** > **Build APK(s)**.

Wait for the project to be built.

### Release

Select **Build** > **Generate Signed Bundle / APK...**.

Select 'APK'.

<img src="docs/selectApk.png" width="683" heigh="384">

Choose existing key or create new key. Select 'release' and check both signature versions.

<img src="docs/signatureVersion.png" width="683" heigh="384">

Wait for the project to be built.


### Launch

Download this example of the android [app](https://github.com/aqoleg/blzandroid/releases/download/0.5.0/bluzelle.apk).

Activate the option **Settings** > **Security** > **Unknown sources** in the android device to launch this apk.


