# TensorFlow Android Camera Demo

This folder contains an example application utilizing TensorFlow for Android
devices.

## Description
<br/>
copy paste your pb and label files as 'retrained_labels.txt' and rounded_graph.pb in asset folder and build. enjoy :-)
<br/><br/>
The demos in this folder are designed to give straightforward samples of using
TensorFlow in mobile applications.

Inference is done using the [TensorFlow Android Inference Interface](../../../tensorflow/contrib/android),
which may be built separately if you want a standalone library to drop into your
existing application. Object tracking and YUV -> RGB conversion is handled by
libtensorflow_demo.so.

A device running Android 5.0 (API 21) or higher is required to run the demo due
to the use of the camera2 API, although the native libraries themselves can run
on API >= 14 devices.
