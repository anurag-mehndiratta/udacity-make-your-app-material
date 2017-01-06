# Make Your App Material

This is the Project 5 of Udacity Android Nanodegree.

This app:
- uses gradle to build a joke-telling app, factoring functionality into libraries and flavors to keep the build simple. 
- configures a Google Cloud Endpoints development server to supply the jokes.

This project contains:
- a Java library for supplying jokes
- an Android library with an activity that displays jokes passed to it as intent extras.
- a Google Cloud Endpoints module that supplies jokes from the Java library. Project loads jokes from GCE module via an async task.
- connected tests to verify that the async task is indeed loading jokes.
- paid/free flavors. The paid flavor has no ads, and no unnecessary dependencies.

App retrieves jokes from Google Cloud Endpoints module and displays them via an Activity from the Android Library.