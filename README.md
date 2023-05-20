# GameBoy Overlay

# OVERVIEW

This is an updated version of my GameBoy overlay for RetroArch I made back in 2017 (<a href="https://forums.libretro.com/t/gameboy-touch-overlay/12469">RetroArch Forums</a>).

I've updated it for modern 21:9 (2400x1080) screen Android devices.

# INSTALLATION

<b>1.</b> Download latest release.

<b>2.</b> Extract and copy the <b>gb-portrait</b> folder inside: 
<i>"RetroArch/overlays/misc"</i> (Or any folder you set for overlays in RetroArch settings) and overwrite if asked.

<b>3.</b> Boot any GB or GBC game (the Gambatte core is recommended), go into the menu and change these settings:

<b>Video:</b>
- Enable fullscreen over notch in Android devices <b>ON</b>

<b>Video - Scaling:</b>
- Integer Scale <b>OFF</b>
- Aspect Ratio <b>Custom</b>
- Custom Aspect Ratio (X Position) <b>221</b>
- Custom Aspect Ratio (Y Position) <b>1147</b>
- Custom Aspect Ratio (Width) <b>640 (4x)</b>
- Custom Aspect Ratio (Height) <b>576 (4x)</b>
- Crop Overscan (Restart Required) <b>ON</b>

<b>On-Screen Display - On-Scren Overlay:</b>
- Display Overlay <b><ON</b>
- Auto-Scale Overlay <b>OFF</b>
- Overlay Preset <b>gb</b> (Select the <b>gb.cfg</b> file found in <b>gb-portrait</b> folder)
- Overlay Opacity <b>1.00</b>
- (Portrait) Overlay Aspect Adjustment <b>-0.250</b>
  
Finally go to <b>Quick Menu - Ovverides</b> and <b>Save Core Overrides</b>

<b>Optional Settings:</b>
  
If you use Gambatte core i reccomend this core options:
- GB Colorization <b>Internal</b>
- Internal Palette <b>GB - DMG</b>
- Color Correction <b>GBC Only</b>
- Color Correction Mode <b>Accurate</b>
- Interframe Blending <b>LCD Ghosting (Accurate)</b>
- Emulated Hardware (Restart Required) <b>Auto</b>
- Use Official Bootloader (Restart Required) <b>ON</b> (If you have BIOS files)
  
I also reccomed using a <b>Video Shader</b> like <b>dot.glslp</b> found in <i>shaders_glsl/handheld/</i> (Or <i>shadrs_slang/handheld/dot.slangp</i> if you use Vulkan video driver)
