BODA RUSH - Thika Road motorbike racing game for Android
=========================================================

This folder is a complete Android Studio project. Build it into an APK
in ONE of these two ways.

OPTION A - Android Studio on your PC
1. Install Android Studio (free): https://developer.android.com/studio
2. Open Android Studio > Open > choose this ThikaRoadBodaRush folder.
3. Wait for "Gradle sync" to finish (first time downloads a lot; needs internet).
4. Menu: Build > Build App Bundle(s) / APK(s) > Build APK(s).
5. Click "locate" in the pop-up. Your file is:
   app\build\outputs\apk\debug\app-debug.apk

OPTION B - Build it free on GitHub (nothing to install)
1. Create a free account at https://github.com and make a new repository.
2. Upload all files in this folder (drag and drop on "uploading an existing file").
   Include the hidden .github folder - if your file browser hides it,
   upload the ZIP's contents instead.
3. Open the "Actions" tab. "Build APK" runs automatically (about 5 minutes).
4. Click the finished run, then download "BodaRush-apk" under Artifacts.
   Unzip it to get BodaRush.apk.

INSTALL ON A PHONE
- Send BodaRush.apk to the phone (WhatsApp, USB cable, Google Drive).
- Tap it. Allow "Install unknown apps" for the app you opened it from.
- Tap Install, then open "Boda Rush".

NOTES
- This is a debug build: fine for you and friends to install, not for the Play Store.
  The Play Store needs a signed release build (Build > Generate Signed Bundle).
- The game runs offline. With internet it uses its nicer fonts.
- Phone back button pauses/resumes a ride; on the menus it closes the app.
- The game itself is app/src/main/assets/index.html.
