# Android Face Detection from a Photo

Android Java sample detecting faces in a bundled photograph and drawing bounding boxes.

## How it works

`MainActivity` loads `res/drawable/test1.jpg`, passes a bitmap frame to Google Mobile Vision's `FaceDetector`, draws red rectangles for detected faces and displays the annotated image. The activity also contains a screen wake-lock demonstration.

## Usage

Import the Java sources, Android manifest and resources into an Android Studio application configured with AndroidX AppCompat and the Google Mobile Vision face-detection dependency. Build and launch the activity, then use the detection button.

## Notes

Gradle build files are not included, so this is a source sample rather than a complete Android project. It detects face locations in an image; it does not identify people or compare identities.
