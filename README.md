# SocialSwap (In Progress) 📱
SocialSwap is a mobile app that enables secure and easy exchange of contact information and social links using QR codes, offering a modern alternative to traditional business cards. <br>
Currently in development, it is designed for seamless use at networking events, with future updates aimed at enhancing features and usability.

<em><strong>SocialSwap makes exchanging contacts a breeze - just tap, scan, and connect!</strong></em>

## Purpose of this app 🔥
Meeting new people / person? Want to exchange multiple contacts/socials? SocialSwap is here for the rescue.

The purpose of SocialSwap is to provide a simple and secure solution for exchanging contact information and social links.<br>
Traditional business cards can be cluttered and hard to manage, but with SocialSwap, your important details can be shared instantly via QR codes.<br>
Whether you’re attending an event or just meeting someone new, SocialSwap makes exchanging contact information effortless and helps you stay connected with ease.<br>

## Made With 🛠

- [Kotlin](https://developer.android.com/kotlin/first) - First class and official programming language for Android development.
- [Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) - For asynchronous calls and tasks to utilize threads.
- [Android Architecture Components](https://developer.android.com/topic/architecture) - Collection of libraries that help you design testable, and maintainable apps.
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes.
  - [ViewBinding](https://developer.android.com/topic/libraries/view-binding) - Generates a binding class for each XML layout file present in that module and allows you to more easily write code that interacts with views.
  - [Room](https://developer.android.com/training/data-storage/room) - Room is an android library which is an ORM which wraps android's native SQLite database
  - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) - LiveData was used to save and store values for viewModel calls and response of method calls.
- [Material Components for Android](https://github.com/material-components/material-components-android) - Material Components for Android (MDC-Android) help developers execute Material Design. Developed by a core team of engineers and UX designers at Google, these components enable a reliable development workflow to build beautiful and functional Android apps.
- [Firebase](https://firebase.google.com/) - Firebase was used as a backend service to provide features like authhentication via Email to authenticate users, Firebase Realtime database was used as a primary databse to store the data of users and their social accounts and Firebase Storage to store and save user's profile picture and banner pictures.
- [ZXing - QR Code Generator](https://github.com/zxing/zxing) - ZXing's QR Code generator library to generate QR Code from Strings.
- [ML Kit - QR Code Scanner](https://developers.google.com/ml-kit/vision/barcode-scanning/android) - To scan QR Code generated by SocialSwap Android App.
- [CameraX](https://developer.android.com/jetpack/androidx/releases/camera) - To enable the feature of QR Code scanning.
- [Glide](https://github.com/bumptech/glide) - To set or place URL, Bitmaps as Image on the screen.
- [Circular Image View](https://github.com/hdodenhof/CircleImageView) - To create a placeholder for profile picture of user.
  <br><br>[The above technologies have been integrated so far, and additional features and improvements are planned for future updates.]

<br>

## Architecture 👷‍♂️

This app uses [MVVM(Model View View-Model)](https://developer.android.com/topic/architecture#recommended-app-arch) architecture.

![Architecture Flow](https://user-images.githubusercontent.com/62587060/216827577-bca54a6a-80c0-4ece-ba06-ac885a1e7f55.png)

## Flow of the app 🗺

![SocialSwap-App-Flow](https://user-images.githubusercontent.com/62587060/219847606-3ccbd2b1-fa1c-46f3-8115-10e570324eac.png)


## Future Release Plans 🚀
Currently in development, the app is being designed for use at networking events, with additional features planned to enhance its usability and functionality.

