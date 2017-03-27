## Appodeal AIR intellij demo
To integrate Appodeal AIR plugin to your intellij idea project:
1. Create lib folder in a root folder of your project and put `Appodeal.ane`, `AppodealPlayServices.ane` and `AppodealSupportLib.ane` into.
2. Unzip assets folder somewhere in your project.
3. Right mouse button on your project name in a project view -> open module settings -> modules -> your app module -> dependencies -> add dependency (green plus on the right corner) -> new library. Select Appodeal's ane files in opened dialog.
4. Choose `Android` tab.
5. In `Application Descriptor` section choose `Custom template` and press button `Create...` (if you don't have custom descriptor).
6. In `Files and folders to package` section press green plus and add content of assets folder from step 2 (not assets folder itself, just a content).

Other steps are the same as in [documentation](https://www.appodeal.com/sdk/documentation?framework=7&full=1&platform=1).