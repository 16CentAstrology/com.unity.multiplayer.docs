---
id: play-mode-scenario-window-reference
title: Play Mode Scenario window reference
description: Descriptions of the properties in the Play Mode Scenario window.
---

This table explains the behavior of each property in the Play Mode Scenarios window.

|**Property**|||**Description**|
|-|-|-|-|
|Description|||Enter a description for this instance. This description exists as a tooltip for this Play Mode Scenario in the [Play Mode Scenario dropdown](play-mode-scenario-dropdown-reference.md). |
|Main Editor|||The instance that exists in the main Unity Editor.|
||Multiplayer Role||The [Multiplayer Role](https://docs.unity3d.com/Packages/com.unity.dedicated-server@1.3/manual/multiplayer-roles.html) that this local instance uses. Unity uses this Multiplayer Role and ignores the Multiplayer Role you assign in the Project Settings window. This property appears when the [Dedicated Server package](https://docs.unity3d.com/Packages/com.unity.dedicated-server@1.3/manual/index.html) exists in your project.
||Tag||One or more reference words that you can use in a script to assign the main Editor Player to a certain behavior. To control whether a player exists on the client or server, use the **Multiplayer Role** property. <br/>You can change the Multiplayer Role in the **File** > **Build Profiles** window.|
||Initial Scene||The scene that all instances display when you initialize them.|
|Editor Instances|||A [virtual player](https://docs-multiplayer.unity3d.com/mppm/current/virtual-players/) that exists in the Unity Editor.|
||Name||The name for this additional Editor instance that appears in the [Play Mode status window](play-mode-scenario-window-reference.md). |
||Multiplayer Role||The [Multiplayer Role](https://docs.unity3d.com/Packages/com.unity.dedicated-server@1.3/manual/multiplayer-roles.html) that this instance uses. Unity uses this Multiplayer Role and ignores the Multiplayer Role you assign in the Project Settings window. This property appears when the [Dedicated Server package](https://docs.unity3d.com/Packages/com.unity.dedicated-server@1.3/manual/index.html) exists in your project|
||Tag||One or more reference words that you can use in a script to assign the main Editor Player to a certain behavior.<br/>To control whether a player exists on the client or server, use the **Multiplayer Role** property.|
|Local Instances|||Instances of this project that run on your local machine.|
||Name||The name of this instance that appears in the [Play Mode status window](play-mode-scenario-window-reference.md).|
||Build Profile||The [Build Profile](https://docs.unity3d.com/6000.0/Documentation/Manual/build-profiles.html) that this instance uses. Select the Build Profile that matches the device you want to build this instance on:<br/>&#8226; Mac Client <br/>&#8226; Android Build Profile <br/>&#8226; Windows|
||Multiplayer Role||The [Multiplayer Role](https://docs.unity3d.com/Packages/com.unity.dedicated-server@1.3/manual/multiplayer-roles.html) that this local instance uses. Unity uses this Multiplayer Role and ignores the Multiplayer Role you assign in the Project Settings window. This property appears when the [Dedicated Server package](https://docs.unity3d.com/Packages/com.unity.dedicated-server@1.3/manual/index.html) exists in your project|
||Run Device||The device this instance builds to and runs on. For information on how to connect an android device to Unity, refer to [Debug on Android devices](https://docs.unity3d.com/Manual/android-debugging-on-an-android-device.html).<br/><br/>This property only appears when you select the **Android Build Profile.** |
||Advanced Settings||Optional properties that you can use to debug and control this local instance. |
|||Stream Logs To Main Editor|Select the checkbox to display logs from this instance in the Unity Editor Console.|
|||Logs Color|The color this instance uses to display logs in the Unity Editor.|
|||Arguments|The [UGS launch parameters](https://docs.unity.com/ugs/manual/game-server-hosting/manual/concepts/launch-parameters) that modify this instance.|
|Remote Instances|||Instances that exist in the [Unity Cloud](https://docs.unity.com/cloud/en-us) and use [Unity Gaming Services (UGS) Multiplay Hosting](https://docs.unity.com/ugs/en-us/manual/game-server-hosting/manual/welcome-to-multiplay).|
||Name||The name of this instance that appears in the [Play Mode status window](play-mode-scenario-window-reference.md).|
||Identifier||The label, in a string, that determines the name of the Multiplay build, fleet, and server. This string field uses the format `CreatedFromTheUnityEditor-[identifier]-[username]`. Don't use any special characters.|
||Multiplayer Role||The [Multiplayer Role](https://docs.unity3d.com/Packages/com.unity.dedicated-server@1.3/manual/multiplayer-roles.html) that this remote instance uses. Unity uses this Multiplayer Role and ignores the Multiplayer Role you assign in the Project Settings window. This property appears when the [Dedicated Server package](https://docs.unity3d.com/Packages/com.unity.dedicated-server@1.3/manual/index.html) exists in your project|
||Advanced Settings|||Optional properties that you can use to debug and control this remote instance. |
|||Fleet Name|The name of the server fleet to display in the Multiplayer Hosting environment. |
|||Fleet Region|The server region this instance runs from.|
|||Instance Amount of Cores|The amount of CPU cores this remote instance requests from the server.|
|||Instance Memory|The amount of memory, in megabytes, that this instance requests from the server. To learn how much memory your project uses, use the [memory profiler package](https://docs.unity3d.com/Packages/com.unity.memoryprofiler@1.1/manual/index.html).|
|||Instance CPU Clockspeed|The amount of CPU time, in megahertz, that this instance requests from the server.|
|||Stream Logs To Main Editor|Select the checkbox to display logs from this instance in the Unity Editor Console.|
|||Logs Color|The color of text that displays in the Unity Editor for logs that relate to this instance.|
|||Arguments|The [UGS launch parameters](https://docs.unity.com/ugs/manual/game-server-hosting/manual/concepts/launch-parameters) that modify this instance.|

## Additional resources
* [Create a Play Mode Scenario](play-mode-scenario/play-mode-scenario-create.md)
* [Test live instances locally and remotely](play-mode-scenario/play-mode-scenario-about.md)
* [Play Mode Scenarios requirements and limitations](play-mode-scenario/play-mode-scenario-req.md)
