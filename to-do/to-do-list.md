# 2019

## 2019.31

Add bulk edit of controller type.

Double click in morph effect assist sends corners to their maximums.

Add ZCPP protocol support.

In Model Faces, States and import dialogs remember any custom colours between accesses to the colour dialog.

Add support for convert node data to effects at the strand and model level to reduce the tedium of converting each node individually.

Consolidate custom model node missing errors to one where missing nodes are contiguous.

Add a link to install vamp plugins when creating timing tracks on a musical sequence and vamp is not installed.

Make it easier to open sequence backups directly.

Optionally pull text from a lyric track for the text effect.

Add lead in time and speed controls to Shader effect \(includes ability to run time backwards\).

Download shader if name in tree is double clicked on.

Make transition hints optional and work even if effect backgrounds not being displayed.

## 2019.30

In MIDI events add the ability to discern non zero data 1/2.

Add an active property to models so you can hide models from display.

## 2019.29

Add a Shader download option for known good shaders.

Add the ability to prevent some double midi events where the event is not using key on/off.

Warn in check sequence if trying to use shaders on openGL less than v3.

Add the ability to control gravity in liquit effect.

Allow xFade to work with multiple MIDI controllers at once.

## 2019.28

Add filename tooltip to colour curve buttons.

Add shader effect.

When importing a timing track from xLights sequence and the name clashes overwrite if there are no existing timing marks.

Allow xSchedule to access more than one MIDI device at once.

Add "Set step position" and "Set step position ms" xSchedule APIs.

Add ability to clone xSchedule playlists, steps, items and schedules.

Add the ability to set the Force Local IP in xSchedule.

Add the delay setting to the text playlist item.

Add check sequence check for matrices where strands/string does not divide evenly into string length.



## 2019.27

Add "Fold" transition type.

Add effects-grid representation of transitions.

Add import of previews and models from another rgbeffects file.

Add some more snowflake styles.

Enhance controller connection bulk edit to allow editing just one property.

When selecting waveform if less than 5 pixels are selected treat it like a click.

When using jukebox always show the effect properties.

Add event support to xSchedule plugins.

## 2019.26

When prompting for missing audio include the original audio filename to make it easier to find.

When audio is missing look down 1 folder and grab it from there if found.

Add plugin functionality to xSchedule. See "Plugin Docuentation.txt" in github for the interface specification. Also in github is a C\# plugin wrapper with simple UI.

Move SMS Daemon to be an xSchedule plugin.

Suport a "-shimmer" suffix on phonemes which will shimmer the phoneme mouth. This needs to be manually added where you want it.

When dropping a video file and creating a video effect get smarter about the length of the effect created.

Add a right click menu to the test dialog channel lists to quick select/deselect channels/models/outputs.

When editing jukebox button definitions always pop up the dialog near the button.

Add a set mode api to xschedule to turn on/off master and remote modes.

Add preset length to effect preset panel.

Add a CTRL-A keyboard shortcut to layout panel to select all models.

Save audio volume between xLights runs.

## 2019.25

Add some extra modes to VU Meter that act like timing mark controlled sweeps for arches.

Add support for scss palette files.

Allow user to control model handle sizes.

Added Ellipse to Shapes Effect.

Added Rotation to the Present, Tree, Heart, and Crucifix in the Shapes Effect.

## 2019.24

Add xFade ability to control xLights on multiple machines.

## 2019.23

Add manual link to help menu.

## 2019.22

Add right click print to controller visualizer.

Add right click export to csv file to controller visualizer.

Updated Sandevice upload to support color order, brightness, group count, null pixel, and reverse controller settings on FIRST model.

Add Sandevice Controller types to e1.31 dialog.

Upgrade J1SYS P12 support to support a broader range of models.

Add the ability to send ArtNET triggers to xSchedule.

Add the ability to receive ArtNET triggers to xSchedule.

Add a character map browser to the shape effect emoji.

## 2019.20

Falcon upload - will upload in "Absolute" mode if Falcon is configured that way, or "Universe" mode if it's configured that way.

ESPixelStick upload will honor color order, brightness, gamma, group count controller settings on FIRST model

Add Controller type to e1.31 dialog, allow selection of Falcon/ESPixelStick. More to come.

Add shift scroll wheel horizontal scrolling to custom model dialog

Add cut to effects grid right click menu

Add alternate pixel wiring to the spinner model

## 2019.19

Increase maximum spirals on the tree model.

Make e131 default to multiple universes ... single output.

Add custom model import onto matrices/trees as submodels including the submodels, faces and states.

Offset models when pasting them if same model in the same location.

## 2019.18

DDP outputs can record the controller type \(hat/cape\) and upload menu item only shows it

"Discover" button on setup tab to discover and automatically add/configure FPP instances

Add "Visualise" option for DDP/FPP controllers to see layout of models on controller

FPP Connect can update the start channel of matrices for LED panel capes

~~FPP Connect can detect LED Panel capes, display the matrix size~~

~~Ability to use "Controller description" for starting channel \(DDP only right now\)~~

Add a LOR S5 LOREDIT file import

~~Use a dropdown for selection of Force IP address~~

## 2019.17

Add falcon smart remote support

Add ability to split timing marks in half

Show node count in model list tooltip

## 2019.16

Added Cut/Copy/Paste Support for 3D Objects in the Layout Tab

Added Arrow Key Support for 3D Objects in the Layout Tab

Added Right Click Menu for Canvas Layers Selection. Select All, Deselect All, Select Layers With Effects

Add yet more wiring options to the cube model

Expand pixlite upload to support all pixlite and LOR pixcon versions

## 2019.15

All screen map area to be manipulated using the mouse

Add a frame audio waveform to the VUMeter

## 2019.14

Add logarithmic x axis to spectragram

Add line spectragram to vu meter

Add circle line spectragram to vu meter

## 2019.13

Add the kaleidoscope effect

Add ctrl/ctrl-shift constraints to sub-buffer corner moves

Add ctrl/ctrl-shift constraints to morph assist panel corner moves

Allow fireworks x/y location to work independently. If only one is set only that axis is constrained

## 2019.12 

~~Added Subfolder Selection to Batch Render Dialog~~

Add lines effect

Make hold color an option on shapes effect

Rework morph effect assist gestures to be more like the sub-buffer panel

Add color palettes to the install

## 2019.11

Add shift move to morph effect assist

Upgrade pixlite controller upload for the 16 Long Range

Allow material files to be left in a subfolder under obj file location as long as it is referenced in the material file

Add bulk edit to the morph swap points button

Make the row header resizable

## 2019.10

Add an  &lt;All&gt; state to state effect that activates all states. Also recognize \* in timing track as well

If models on a port are not using contiguous channels put them on virtual strings

Include xmap files in the backup

Increase maximum lines read from file to 20 for text effect

Add option to convert tool for creating LEDBlinky animation files.

## 2019.09

Add movement to shapes effect

~~Add tool for applying reaper or xAudio edits to one or more audio files and generate a new audio file~~ 

Refactor the fireworks effect including new settings and new value curves

Add gain to VUMeter

Add an inverted music value curve

Add gain to music value curve Render cache effects which have blur or rotation applied

## 2019.08

Add channel remapping to the DMX effect

Add an option for 2D preview to move the 0.0 location to the middle bottom

Added rotation to the Shape Effect

Added Value Curve to Ripple Rotation Setting

## 2019.07

Add inside/outside ratio to star model

Add zoom gesture to Preview Panels.

Add Mac TouchPad/MagicMouse "wheel" event handling to Preview Panels.

Allow cube and sphere to be exported as 3D custom models

Make green box on 2D layout optional

Add right click reset camera position to house preview and layout

Update J1SYS P2 upload to support more model configurations

Add bulk edit to effect type

## 2019.06

Make model move accelerate when using keyboard when repeatedly moving models using keyboard 

Add sphere model

Increase maximum hollow size on spinner

## 2019.05

Add Easylights controller upload

## 2019.04

Add pan based on viewing angle in 3d 

I~~mplement advanced FPP connect dialog including: Discovery of FPP instances, Instance by instance settings controls over what is uploaded, Sparse FSEQ uploading, Compressed FSEQs~~

Add keyboard shortcuts to sequence save dialog

Add cube model

Add value curve flipping

## 2019.03

~~Add a 2D value curve generator~~

## 2019.02

## 2019.01

Add 3d

