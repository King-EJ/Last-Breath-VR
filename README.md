LAST BREATH VR  -  VR mod (Unity 6000.3, IL2CPP x64, URP, BepInEx 6)
====================================================================
Version 0.1.4 (test build)

<img width="1839" height="855" alt="Last Breath_ VR Ruins" src="https://github.com/user-attachments/assets/3c3b580a-a47e-4ff8-93a4-a478e3af1a24" />


The level is a 3D DIORAMA in front of you - a little side-scrolling world on a table - and it glides along after
the player. Play with your normal Xbox controller (the game reads it itself); the VR controllers are not needed.

INSTALL
unzip to game folder, only tested with virtual desktop XR



XBOX CONTROLLER
  Everything ............ the game's own controls
  L3 + R3 held 1 s ...... VR SETTINGS MENU (stick / D-pad choose and change, A select, B close; the game gets no
                          controller input while it is open)
  L3 + R3 tapped ........ re-centre the view (look straight ahead at the diorama when you do it)

VIEW
  * Diorama (default\R3 toggle): the level looks DioramaScale (8) times smaller, the player's lane DioramaDistance (0.9 m) in
    front of you, you a little above it. The diorama stays still while the player moves inside a small box, then
    glides after; a door / new room = it jumps there. Lean in to look closer - the world is all real 3D.
  * GameCamera: you are where the game's camera is, life size (VR settings > View).
  * Menus / full-screen game screens: the game's picture on a solid screen in front of you. The HUD floats in front
    of you over the diorama (see-through).
  VR settings > View: diorama scale, distance, height, to the side, centred on the player, glide speed, free box.


CHANGES
0.1.7 
  * NEW: a small dot over every door and portal (ways up / down, level changes). White while you are away, it turns
        green (and pulses) the moment the game lets you use it - no waiting for the floating prompt to fade in.
        Always drawn on top. VR settings: "Dots over doors / ways up or down", "dot size", "dot height"
        ([View] DoorDots / DoorDotSize / DoorDotHeight).
  * Subtitles (NPC talk) and tips now float on their own, apart from the HUD icon stack. Move and resize them in
        the VR settings (hold L3 + R3): "subtitles size", "distance (forward / back)", "up / down", "left / right"
        ([View] SubtitlesSize / SubtitlesDistance / SubtitlesHeight / SubtitlesSide). "Subtitles / tips on their own"
        off puts them back just under the HUD icons.
  * HUD: the icon groups (counters, health / weapon / ammo ...) float together in the MIDDLE in front of you, top
        group first. VR settings > View: icons size, distance (forward / back), up / down
        ([View] HudIconsCentred / HudIconsSize / HudIconsDistance / HudIconsHeight).
  * Pick-up / use prompts (e.g. "Nail Bat  A") float in the 3D world over the thing itself, a little bigger
        ([View] WorldPromptScale = 1.5), not on the HUD.

Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.
