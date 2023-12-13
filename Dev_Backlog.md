# Dev Backlog / Tasks Report - WineSip

**General Information**
- **Project Name:** WineSip
- **Development Team:** La Bruja Dev Team
- **Start Date:** August 24, 2023
- **Estimated Completion Date:** -- -- --

## DEVLOG

### Development
| Subject | Description | Current Status | Platform | Completion Date |
|----------|----------|----------|----------|----------|
| Image Cropper  | Implemented "Image Cropper" in 'Edit Profile' to updaload a new profile picture (Photo frame clipped as a circle) and 'Taste new wine' to upload a new wine bottle picture (Photo frame clipped as a vertical 9:16 aspec ratio rectangle).  | 🟢Done   | 🍎🤖   | December 3, 2023   |
| Stripe Implementation  | In this release, we implemented Stripe payments seamlessly using the 'flutter_stripe' package in Flutter  with enhanced security features.  | 🟢Done   | 🍎🤖   | November 21, 2023   |
<!-- ### Performance -->
<!-- ### Design UI Updates -->
### Bug Fix
| Subject | Description | Current Status | Platform | Completion Date |
|----------|----------|----------|----------|----------|
| WillPopScope Class Deprecation  | Flutter version 3.12.0-1.0.pre deprecated the 'WillPopScope' class, traditionally used for handling back button presses. The new 'PopScope' class has been introduced to replace it, offering improved functionality and addressing limitations. We updated our code to utilize 'PopScope' for more effective management of back button behavior in the WineSip application.  | 🟢Done   | 🍎🤖   | December 5, 2023   |
| Fixed build phase apk errors  | Addressed errors in the APK build process, optimized APK signing, and streamlined Gradle scripts for a more stable build.  | 🟢Done   | 🍎🤖   | November 26, 2023   |



## List of Pending Tasks

| Task         | Description                                 | Priority | Current Status | Estimated Start Date | Estimated Finish Date | Responsible |
|--------------|---------------------------------------------|----------|----------------|-----------------------|------------------------|-------------|
| 1. Widget vintage     | Slow Widget, too many elements, implement load on drag/scroll                 | --     | 🟢Finished    | --        | --        | Cristian D.        |
| 2. Register wine  | Alert user if any field is empty before submitting a wine to db | --     | 🟢Finished    | August 30, 2023       | Septempber 1, 2023        | Cristian D.       |
| 3. Launcher Icons   | Set launcher icons              | --   | 🟢Finished    | --       | --        | Cristian D.      |
| 4. Spash Screen      | Implement Splashscreen for app         | --   | 🟢Finished    | --       | --      | Cristian D.         |
| 5. Animated Switcher      | fix the AnimatedSwitcher to have an animation (scale* or fade) after taking a picture to a wine         | --   | ⚪Dispose    | --       | --      | Cristian D.         |
| 6. Aft. Effct. Anim.      | Create After Effects Animation for the wine photo placeholder.         | --   | ⚪Dispose    | --       | --      | Cristian D.         |
| 7. Image File Size reduction      | Use this library to reduce Image file size without loosing noticeable image quality, Package 99% Flutter popularity:  https://pub.dev/packages/flutter_image_compress       | --   | 🟢Finished    | --       | --      | Cristian D.         |
| 8. Secondary aromas      | Create all Secondary aromas icons and widgets         | Medium   | 🚧Working    | --       | --      | Cristian D.         |
| 9. Implement GUIDE      | Implement user guidance for tasting wine and using the "Taste new wine" page, using Flutter's ShowCaseView Library from PubDev https://pub.dev/packages/showcaseview !!! new idea - task #14 !!!      | --   | ⛔Delegate task #14    | --       | --      | Cristian D.         |
| 10. Social Sharing wine card      | Implement social sharing on the Wnie Card by using the following package https://pub.dev/packages/share_plus        | --   | 🟢Finished / not Facebook    | --       | --      | Cristian D.         |
| 11. Click Suggestions      | Click on Wines - Suggs - Favs from the user card on homepage to open dialog listing each one        | --   | 🟢Finished    | --       | --      | Cristian D.         |
| 12. TextFields verifications      | Change all for "CupertinoTextField"'s and set maxCharacter Length and disable special characters for each one.        | Medium   | ❄️Not Started    | --       | --      | Cristian D.         |
| 13. Social Links      | Links to their social networks so communication is unrequired.        | Medium   | ❄️Not Started    | --       | --      | Cristian D.         |
| 14. Guided wine taste NEW       | New Step-by-step (widget by widget) guided wine taste in the format of Illustration - Description or instruction - Widget on a "Column" manner.        | High   | ❄️Not Started    | --       | --      | Cristian D.         |
| 15. Taste a Wine 2.0       | Recreate the "Taste new wine" page, Dispensing with 'Provider' and making use of 'Callback Functions'        | --   | 🟢Finished    | --       | --      | Cristian D.         |
| 15. Extra elements for Tasting wine       | -Wine type selection(Red, white, etc), Switches for widgets        | --   | 🟢Finished    | --       | --      | Cristian D.         |




<br>
<br>
<br>


## Pre-launch checklist

| Task         | Description                                 | Priority | Current Status | Estimated Start Date | Estimated Finish Date | Responsible |
|--------------|---------------------------------------------|----------|----------------|-----------------------|------------------------|-------------|
| 1. Launcher Icons     | Launcher icons and name have not being set up correctly                 | --     | 🟢Finished    | --        | --        | Cristian D.        |
| 2. Terms & Conditions     | Lack of "Terms & Conditions" agreement                 | Medium     | ❄️Not Started    | --        | --        | Cristian D.        |
| 3. Graphics Copyright     | Recreate/Replace every icon and Vector graphics from the app (most are copyrighted)                 | Medium     | ❄️Not Started    | --        | --        | Cristian D.        |
| 4. LOAD ON SCROLL (PAGINATION)     | Load more item when scroll down (so far called pagination) on every list on the app, mainly on the "people tab screen"                | HIGH     | ❄️Not Started    | --        | --        | Cristian D.        |


## Known issues

**Unresponsive SalomonBottomBar**
- SalomonBottomBar currently not working together with Flutter's Screen_util package.

**Spash Screen no image on Android 12**
- It appears that there is currently an [issue](https://github.com/jonbhanson/flutter_native_splash/issues/626#) preventing the image from overlaying in top of the background color as intended when utilizing "flutter_native_splash" on Android 12 API level 31/32, even when implementing their own android_12 configuration suggestion on their [Documentation](https://github.com/jonbhanson/flutter_native_splash).



## others

**Additional Notes**
- None

**Review Date**
- October 12, 2023

**Signature**
- [Cristian delgadillo]

**Distribution**
- Development Team
- Project Management
