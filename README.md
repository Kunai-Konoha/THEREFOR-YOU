# THEREFOR YOU VERSION 1.0

### Overview

This app performs recognition of (Antropogenic Disaster) speech Commands on mobile, reacting to the spoken word.

Guided from : https://github.com/tensorflow/examples/tree/master/lite/examples/speech_commands/android

Try our Interface for future : https://www.figma.com/proto/R7fP5qylP8myunm7Yin9vc/hackathon-test?node-id=1%3A734&scaling=min-zoom

<!-- TODO(b/124116863): Add app screenshot. -->

## Build the demo using Android Studio

### Prerequisites

* If you don't have already, install **[Android Studio](https://developer.android.com/studio/index.html)**, following the instructions on the website.

* You need an Android device and Android development environment with minimum API 21.
* Android Studio 3.2 or later.

### Building
* Open Android Studio, and from the Welcome screen, select Open an existing Android Studio project.

* From the Open File or Project window that appears, navigate to and select the THEREFOR YOU/android directory from wherever you cloned the GitHub repo. Click OK.

* If it asks you to do a Gradle Sync, click OK.

* You may also need to install various platforms and tools, if you get errors like "Failed to find target with hash string 'android-21'" and similar.
Click the Run button (the green arrow) or select Run > Run 'android' from the top menu. You may need to rebuild the project using Build > Rebuild Project.

* If it asks you to use Instant Run, click Proceed Without Instant Run.

* Also, you need to have an Android device plugged in with developer options enabled at this point. See **[here](https://developer.android.com/studio/run/device)** for more details on setting up developer devices.


### Model used
Download the model from **[here](https://storage.googleapis.com/download.tensorflow.org/models/tflite/conv_actions_tflite.zip)**. Extract the zip to get the .tflite and label file.

The percentage displayed is average command recognition over a window duration (1000ms).

### Additional Note
_Please do not delete the assets folder content_. If you explicitly deleted the files, then please choose *Build*->*Rebuild* from menu to re-download the deleted model files into assets folder.

