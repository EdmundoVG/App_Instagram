# App_Instagram
Android Studio developed app that allows to previsualize an image and share it on instagram.

-----Instagram Image Sharing Android App-----

Project Overview
This Android application allows users to select an image from their device's gallery and share it directly to Instagram. The project was developed as part of a mobile application development course focusing on data persistence and connectivity.
Features

Select images from device gallery
Preview selected images
Share images to Instagram
Fallback sharing option to other compatible apps

-----Prerequisites-----

Android Studio
Android device or emulator
Instagram app installed (recommended)

-----Installation-----

Open the project in Android Studio
Ensure you have the necessary SDK and build tools installed

Key Components:

-----Permissions-----
The app requires permission to read external storage:
xmlCopy<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />

-----Main Functionality-----
Image Selection: Users can pick an image from their gallery
Image Preview: Selected image is displayed in the app
Instagram Sharing: Direct sharing to Instagram or fallback to other apps

-----Code Structure-----
Key Methods:
openImageSelector(): Opens device gallery for image selection
onActivityResult(): Processes selected image and updates preview
shareImageToInstagram(): Handles image sharing logic

-----Limitations-----

Requires Instagram to be installed on the device
Does not use Instagram Graph API for direct upload
Works only with image files

