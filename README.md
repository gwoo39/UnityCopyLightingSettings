# Copy Lighting Settings for Unity

The "Copy Lighting Settings" package allows you, as the name might suggest, to copy&paste lighting settings from one scene to another.

The need for this functionality is based on an Unity [forum thread](https://forum.unity.com/threads/copy-lighting-settings-from-scene-to-scene.308634/), where several community members wonder how to transfer the lighting settings from one scene to another.

I found this to be an interesting problem to solve and thus looked into it. In the video below, I show how the tool can be used.

[![](http://img.youtube.com/vi/-TQzrVn1kWM/0.jpg)](https://youtu.be/-TQzrVn1kWM "")

This package is only interesting if you use Unity 2019.4 and older versions. Unity Technologies improved the lighting workflow in Unity 2020.1, here is a quote from their release notes:
> GI: Added all lightmap settings as an asset. This will allow the user to share them between scenes or switch them out in an easy way.
https://unity3d.com/unity/alpha/2020.1.0a14


# Installation in Unity 2019.3 and 2019.4

In Unity's Package Manager, choose "Add package from git URL" and insert one of the Package URL's you can find below.

## Package URL's

| Version  |     Link      |
|----------|---------------|
| 1.3.0 | https://github.com/pschraut/UnityCopyLightingSettings.git#1.3.0 |


# Installation in older Unity versions

If you use an older Unity version than 2019.3, the Package Manager might not exist or might not have git support yet.

In this case, I believe the easiest way is to only download the `Editor/CopyLightingSettings.cs` file from this repository and save it in your project under `Assets/Editor/CopyLightingSettings.cs`.
