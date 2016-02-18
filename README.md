# OSVR Developer Documentation

# Introduction to OSVR
- [Introduction to OSVR](http://osvr.github.io/whitepapers/introduction_to_osvr/)
- [OSVR feature list](featurelist.md)
  - [Notes on Android support](Introduction/Android.md)
  - [Notes on Linux support](Introduction/Linux.md)
  - [Notes on OSX support](Introduction/OSX.md)
- [List of supported devices, engines and operating systems ](http://osvr.github.io/compatibility/)
- [List of OSVR partners](http://osvr.org/partner.html)
- [OSVR presentations and speaker notes](http://osvr.github.io/presentations/)


# Using OSVR
## Getting Started
- [HDK Unboxing and Getting Starting](Getting-Started/HDK/HDK-Unboxing-and-Getting-Started.md)

## Installing OSVR
- [Windows](Getting-Started/Installing/windows.md)
  - [Download pre-compiled binaries and drivers](http://osvr.github.io/using/)
  - [Install and test RenderManager](installing/RenderManager.md)
- [Linux](Getting-Started/Installing/Linux-Build-Instructions.md)
  - [Very generic instructions](Getting-Started/Installing/linux.md)
- [Android](https://github.com/OSVR/OSVR-Android-Build#readme)
- [OS X](Getting-Started/Installing/osx.md)

## Running the OSVR Server
Running the OSVR server just requires passing it a configuration file. For example:
**osvr_server osvr_server_config.json**

if no parameter is specified, a default file is used.

## Configuring OSVR
- [Calibrating the video-based tracker](Getting-Started/HDK/Video-Based-Tracking-Calibration.md)
- [Local and distributed client/server configurations](Configuring/LocalAndRemote.md)
- Device-specific configuration
  - [OSVR HDK](Configuring/osvrhdk.md)
- [Integrating with VRPN devices](https://osvr.github.io/whitepapers/vrpn_in_osvr/)

## Utilities
- Bundled with OSVR-Core binary snapshots/included in the OSVR-Core source tree:
  - osvr_print_tree
  - osvr_reset_yaw
  - osvr_list_usbserial
  - [PathTreeExport](http://resource.osvr.com/docs/OSVR-Core/md_doc_PathTreeExport.html)
- [TrackerViewer](https://github.com/OSVR/OSVR-Tracker-Viewer/blob/master/README.md)
  - [Additional Tracker Viewer documentation](http://osvr.github.io/doc/tracker-viewer/)
- [OSVR Control](Utilities/OSVRControl.md)
- [Distortionizer](https://github.com/OSVR/distortionizer/blob/master/README.md) helps measure distortion parameters for HMDs
- [Latency tester](https://github.com/sensics/Latency-Test). Open-source Arduino-based latency tester

## Troubleshooting
- [OSVR server](Troubleshooting/OSVRServer.md)
- [Render Manager](Troubleshooting/RenderManager.md)
- [Device-specific information](Troubleshooting/DeviceSpecific.md)
- [Performance optimization using Event Tracing for Windows](http://osvr.github.io/presentations/20150901-Intro-ETW-OSVR/)

# Developing with OSVR
- Setting up the development environment
  - [Windows](Developing/Windows-Build-Environment.md)
- [Directory of projects](http://osvr.github.io/contributing/)
- [Creating an OSVR project](Developing/creating.md)
- [OSVR interfaces](Developing/interfaces.md)
- [Useful resources and tools](Developing/resources.md)
- Device-specific information
  - [OSVR HDK interface](developing/OSVRhdk.md)

# Integrating with Game Engines

- [Unity](https://github.com/OSVR/OSVR-Unity/blob/master/GettingStarted.md)
  - [Tutorial video](https://www.youtube.com/
watch?v=TtLn6XpEisw)
  - [Unity VR demos](https://github.com/OSVR/Unity-VR-Samples) are OSVR versions of the standard VR demos that ship with Unity 5.3
  - [Palace demo](https://github.com/OSVR/OSVR-Unity-Palace-Demo) is a Unity demo illustrating how to use the Unity OSVR plugin
  - [Migrating Oculus Unity apps to OSVR](http://access.osvr.com/binary/download/misc_assets/Migrating%20Unity%20applications%20from%20Oculus%20to%20OSVR%20Mar-11-15.pdf)
- [Unreal](https://github.com/OSVR/OSVR-Unreal/blob/master/README.md)
  - [Tutorial video](https://www.youtube.com/watch?v=u4Y9pUisL1M)
  - [Additional Documentation](https://github.com/OSVR/OSVR-Unreal/blob/master/Documentation.md)
- [OpenVR/SteamVR](https://gitter.im/OSVR/SteamVR-OSVR)
- [Blender](https://github.com/BlendOSVR/OSVR-Blender)
- WebVR
- CryEngine
- [Monogame: video](https://www.youtube.com/watch?v=doOOLaIuj48)
- OpenGL

# Extending OSVR
- [Adding a New HMD](Extending-OSVR/AddingHMD.md)
- [Adding a new Device](Extending-OSVR/Adding-a-New-Device.md)
  - [Best practices for device descriptor](Extending-OSVR/Device-Descriptor-Practices.md)
- [Writing an OSVR Plugin](http://resource.osvr.com/docs/OSVR-Core/TopicWritingDevicePlugin.html)
- [Writing an OSVR Client](http://resource.osvr.com/docs/OSVR-Core/TopicWritingClientApplication.html)
- Porting to a New Operating System

# Roadmap
- In September 2015, RoadToVR published an article by [Yuval Boger](https://twitter.com/osvrguy) of Sensics about the OSVR roadmap. It is an excellent starting point to understand the OSVR big picture and roadmap. [The article can be found here](http://www.roadtovr.com/osvr-roadmap-creating-an-ecosystem-of-interoperable-vr-hardware-and-software/).
- The [OSVR Waffle Board](Roadmap/waffle.md) contains an overview of issues currently in GitHub issue trackers for all OSVR framework projects.
- Additional development priorities suggested by the core OSVR team can be [found here](Roadmap/additional.md).

# Getting Support
## Free support
- Post an issue on the [OSVR Github projects](https://github.com/osvr) to be addressed by the OSVR community
- Open a support ticket on the [support portal](http://support.osvr.org) (or email "support at osvr.org") to be addressed by core developers
- [Visit the OSVR development chat rooms](https://gitter.im/orgs/OSVR/rooms)

## Paid support
Some companies such as [Sensics](http://sensics.com/contact-us/) provide premium support services for OSVR including phone support, system engineering, authoring drivers or integration help. If you require support beyond the free support options, consider contacting the premium providers.

# Additional information
- [OSVR mailing lists and newsletters](http://osvr.github.io/mailing-lists/)
- [OSVR marketing Web site](http://www.osvr.org)
- VR Knowledge Nuggets
  - [Tracking](VR-Knowledge-Nuggets/tracking.md)
  - [Displays](VR-Knowledge-Nuggets/displays.md)
- [The VRGuy's blog](http://www.vrguy.net) often covers OSVR-related topics and includes tutorials such as:
  - [What is geometric distortion (and why should you care)?](http://vrguy.blogspot.com/2013/07/what-is-geometric-distortion-and-why.html)
  - [Converting diagonal FOV and aspect ratio to horizontal and vertical FOV](http://vrguy.blogspot.com/2013/04/converting-diagonal-field-of-view-and.html)
  - [TV screen size vs. goggle field of view](http://vrguy.blogspot.com/2013/04/tv-screen-size-vs-goggle-field-of-view.html)
  - [How things work: the dual-elements optics of the OSVR HDK](http://vrguy.blogspot.com/2015/01/how-things-work-dual-element-optics-of.html)
  - [What is binocular overlap and why should you care?](http://vrguy.blogspot.com/2013/05/what-is-binocular-overlap-and-why.html)
  - [What you should know about head trackers](http://vrguy.blogspot.com/2013/05/what-you-should-know-about-head-trackers.html)
  - [An overview of positional tracking technologies for VR](http://vrguy.blogspot.com/2014/05/an-overview-of-positional-tracking.html)

# Sample third-party projects that integrate OSVR into them
- [OSVR plugin for FreePie](https://github.com/thomasgauthier/FreePIE-OSVR)
