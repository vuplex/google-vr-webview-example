# Google VR WebView Example

This Unity project demonstrates how to use the [Vuplex 3D WebView asset](https://developer.vuplex.com/webview/overview) with Cardboard and Daydream. It includes the [GVR Unity SDK](https://github.com/googlevr/gvr-unity-sdk), so the only thing you must import is the 3D WebView plugin for [Android](https://assetstore.unity.com/packages/tools/gui/3d-webview-for-android-137030) or [iOS](https://assetstore.unity.com/packages/tools/gui/3d-webview-for-ios-137040) ([or both](https://assetstore.unity.com/packages/tools/gui/3d-webview-for-android-and-ios-135383)).

<p align="center">
  <img alt="demo" src="./demo.gif" width="480">
</p>

## Steps taken to create this project

1. Created a new project with Unity2018.1 ([feead00](https://github.com/vuplex/google-vr-webview-example/commit/feead0081831aab2dfbc6406624a000b84385d30))
2. Installed [v1.190.1](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.190.1) of the [Google VR SDK for Unity](https://github.com/googlevr/gvr-unity-sdk) ([62c89bc](https://github.com/vuplex/google-vr-webview-example/commit/62c89bc13332c2d89b241967fca96dd26e53da31))
3. Imported the [Vuplex 3D WebView asset](https://developer.vuplex.com/webview/overview) ([.gitignore](https://github.com/vuplex/google-vr-webview-example/blob/8ccffc78e1785a094150304d29bc09012f958609/.gitignore#L65))
4. Copied the HelloVR demo scene from the GVR SDK to create a new GvrWebViewDemoScene that adds the [WebViewPrefab](https://developer.vuplex.com/webview/WebViewPrefab) and [Keyboard](https://developer.vuplex.com/webview/Keyboard) from the Vuplex 3D WebView asset ([f421e67](https://github.com/vuplex/google-vr-webview-example/commit/f421e6794cdedbf9c41b452986b7f2c8e2826e33#diff-22a82d089493fd288fc7c1102c2f124fR1))

## License

The GvrWebViewDemo.cs script is Copyright (c) 2019 Vuplex Inc and is licensed under the MIT license.

The files in Assets/GoogleVR are from the GVR Unity SDK, the license for which is included in LICENSE.txt.
