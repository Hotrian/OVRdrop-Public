![logo](http://ovrdrop.hotrian.com/resources/OVRdropLogo.png)

# Public issue tracker for OVRdrop

### This repo is the public issue tracker for OVRdrop on Steam

OVRdrop was previously known as [OpenVRDesktopDisplayPortal](https://github.com/Hotrian/OpenVRDesktopDisplayPortal)

OVRdrop is a Utility Application for SteamVR that can mirror a Desktop Window, an entire Monitor, or a WebCam into a Cross Game SteamVR Overlay. OVRdrop works on SteamVR and should be fully compatible with any SteamVR headset, though you will need tracked controllers for many of the features. It is known to work for the HTC Vive as well as the Oculus Rift, though some games may not be compatible with the Rift. The only major downside is that Cross Game Overlays will always draw on top of game geometry because Depth information is not fed to the Compositor by SteamVR games.

### Features

- Can clone almost any Desktop Window into VR.
- Can clone an entire monitor into VR.
- Can clone WebCam sources into VR.
- Side By Side 3D support for displaying Side By Side 3D content into VR.
- Works with almost any SteamVR Compatible game. Should work with any game that utilizes the SteamVR SDKs. On the Rift, certain Rift games will use the Oculus SDK even when you use SteamVR. On the Vive and other SteamVR compatible headsets every game should work.
- Easily Attach the Overlay to the World, the Screen (like a HUD), or one of the Controllers.
- Send Mouse Clicks through to the target application, without leaving VR. (World/Controller attached Overlays only). Allows for Left, Right, and Middle Click as well as ScrollWheel (Horizontal and Vertical wheels).
- Move, Rotate, and Scale the Overlay without leaving VR. (World attached Overlays only).
- The Overlay can Animate when you look at it, such as changing transparency, scale, or moving out of the way.
- Allows configurable Capture FPS.
- Allows configurable Crop Region. You can clone just a subset of a window instead of the whole window if desired.
- Configurable Outline for the Overlay (can disable if desired) to make the Overlay more visible.
- Configurable Quality Settings. Clone a window as is or use Bilinear or Trilinear filtering to smooth edges, increasing perceived quality.
- Options to enable display of the Desktop Cursor on the Overlay when it moves over the target application.
- Haptic Feedback support!
- Save/Load support.

[![steamwidget](http://ovrdrop.hotrian.com/resources/steamwidget.png)](http://store.steampowered.com/app/586210)
