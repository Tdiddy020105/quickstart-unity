[![](https://www.banuba.com/hubfs/Banuba_November2018/Images/Banuba%20SDK.png)](https://docs.banuba.com/far-sdk/tutorials/unity/overview)

## Face AR SDK for Unity example  
  
The example of Banuba Face AR SDK integration for Unity.  

## Usage
### Token
Before you commit to a license, you are free to test all the features of the SDK for free. To start it, [send us a message](https://www.banuba.com/facear-sdk/face-filters#form).  
We will get back to you with the trial token.
You can store the token within the app.  

Feel free to [contact us](https://docs.banuba.com/far-sdk/support) if you have any questions.

### How To Run 

1. Clone the repository
2. Download the latest libs package [BanubaSDK-quickstart.unitypackage
](https://github.com/Banuba/quickstart-unity/releases) and import it using Unity.
3. Put your Client Token to the [Assets/Resources/BanubaClientToken.txt](Assets/Resources/BanubaClientToken.txt)
4. Open the Assets/Scenes/SampleScene and click Run.

### How To Import To Your Project 

1. Download the latest assets package [BanubaSDK-import.unitypackage
](https://github.com/Banuba/quickstart-unity/releases) and import it using Unity.
2. Put your Client Token to the [Assets/Resources/BanubaClientToken.txt](Assets/Resources/BanubaClientToken.txt)
3. Open the Assets/BanubaFaceAR/Demo and click Run.

### Important
if you use BanubaSDK-import.unitypackage you need to add BanubaFaceAR/BaseAssets/Scenes/LoaderScene.unity for Windows and Android Build and set Scene for loading like on the image below:
![LoaderScene](img/loader_scene.jpg)

### Notes
BanubaSDK-quickstart.unitypackage and BanubaSDK-import.unitypackage contains other scenes:
- BanubaFaceAR/FeatureActionUnits/Scenes/ActionUnitsScene.unity - action units feature example
- BanubaFaceAR/FeatureBeautification/Scenes/BeautificationScene.unity - beautification based on luts
- BanubaFaceAR/FeatureMorphing/Scenes/MorphingScene.unity - morphing feature example
- BanubaFaceAR/FeatureSegmentation/Scenes/SegmentationExample.unity - all segmentation features example
- BanubaFaceAR/Makeup/MakeupExample.unity - makeup api example

Also BanubaSDK-import.unitypackage contains:
- BanubaFaceAR/Demo/BanubaSDKDemo.unity - base demo example with all features

### Docs
You can find more info [here](https://docs.banuba.com/far-sdk/tutorials/unity/basic_integration)
