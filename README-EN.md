
# TapsellPlusB4Aplugin

Impementation of TapsellPlus SDK for Basic4Android

### FAQ and issues
List of already asked questions: [Link](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/issues?q=is%3Aissue)
Create a new issue or ask a new question: [Link](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/issues/new)
Official documentation: [Link](https://docs.tapsell.ir/plus-sdk/b4a/main/)

## Setup
> **NOTE**: B4A v11.0 is recommended to use  
> **Note2**: Use B4A's recommended resources. [Link](https://www.b4x.com/b4a.html)

Follow these steps:  
- Download the plugin zip file. [Download page](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/releases)
- Extract the ZIP file (Using WinRar or ...)
- Move `TapsellPlusB4A.jar` and `TapsellPlusB4A.xml` to B4A's Libraries folder
- Move files in `libs` folder to `additional libraries` folder (or set the `libs` as the additional)
- Open your project and check these libraries (after refreshing):
  - TapsellPlusB4A
  - OKHttp


Go to next step which is usage.

## Usage
First go to [Tapsell plus homepage](https://tapsell.ir/tapsellplus/) and apply to make an application. You need it's appId.

Then with having appId follow these steps:  
- Initialize it
  Add this code to `Sub Globals`:  
  ```vb
    Dim tapsellPlus As TapsellPlus
    Dim tapsellPlusAppId As String = "YOUR_TAPSELL_PLUS_APP_ID"
  ```

  Then add this code to `Activity_Create`:  
  ```vb
    tapsellPlus.Initialize(tapsellPlusAppId)
  ```

To show an ad, visit the official documentation. [Here's](https://docs.tapsell.ir/plus-sdk/b4a/main/) the link

## Question or problem?
List of already asked questions: [Link](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/issues?q=is%3Aissue)
Create a new issue or ask a new question: [Link](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/issues/new)
Official documentation: [Link](https://docs.tapsell.ir/plus-sdk/b4a/main/)