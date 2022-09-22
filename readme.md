- Course: [playlist](https://www.youtube.com/playlist?list=PLlyCyjh2pUe9wv-hU4my-Nen_SvXIzxGB), [materials](https://developer.android.com/courses/fundamentals-training/overview-v2)
- Teachers: Simmi Anand, [Lalit Singh Manral](https://twitter.com/lalitsingh047), [Jocelyn Becker](https://www.udacity.com/course/new-android-fundamentals--ud851)
- Additional materials: [Advanced Android Development](https://developer.android.com/courses/advanced-training/overview),[Associate Android Developer Certification](https://developers.google.com/certification/associate-android-developer/study-guide)

- Component types:
  - **Activity** is a single screen with a user interface
  - **Service performs** long-running tasks in background 
  - **Content provider** manages shared set of data 
  - **Broadcast receiver** responds to system-wide announcements

- Think of Android as a hotel:
  - Your app is the guest 
  - The Android system is hotel manager 
  - Services are available when you request them (intents)
    - In the foreground (activities) such as registration 
    - In the background (services) such as laundry 
  - Calls you when a package has arrived (broadcast receiver)
  - Access the city's tour companies (content provider)


- [Android platform API version distribution](https://github.com/ebelinski/apilevels)
- [IntelliJIDEA keymap reference](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
- [Android roadmap](https://miro.com/app/board/o9J_lpg8J8U=)

- Project folders:
  - **manifests** (Android Manifest file description of app read by the Android runtime)
  - **java** (Java souce code packages)
  - **res** (Resorces [XML] - layout, strings, images, audio files, dimensions, colors, ..)
  - **build.gradle** (Gradle build files)

- Run on a physical device:
  - Turn on Developer Options:
    - **Settings** > **About phone**
    - Tap **Build number** seven times
  - Turn on USB Debugging:
    - **Settings** > **Developer Options** > **USB Debugging**
  - Connect phone to the computer with cable 
  - Windows/Linux additional setup: 
    - [Using hardware devices](https://developer.android.com/studio/run/device)
  - Windows drivers:
    - [OEM USB drivers](https://developer.android.com/studio/run/oem-usb)