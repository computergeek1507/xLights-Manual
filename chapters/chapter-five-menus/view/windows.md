# Windows

## Windows

There are a number of windows that enable simultaneous display of different views in xLights. When xLights first loads, a default set of windows are displayed. Which windows are open can be controlled via the Windows menu by selecting View, Windows and then clicking on the required window to open it. The window is dropped by default on the left side of the screen, however each window can be moved and docked to alternate locations on the same screen or moved to an alternate display screen if connected to your PC/ MAC.

![](../../../.gitbook/assets/image%20%28231%29.png)

![Window Toolbar](../../../.gitbook/assets/image%20%28403%29.png)

### ![](../../../.gitbook/assets/display-elements-icon.JPG) Display Elements

The Display Elements window enables views, Timings as well as models to be defined and updated. Functionality for these functions is described in the Views, Timings and Models section of this document.

![](../../../.gitbook/assets/image%20%28428%29.png)

{% page-ref page="../../chapter-four-sequencer/views.md" %}

### ![](../../../.gitbook/assets/model-preview-icon.JPG) Model Preview

The Model Preview window displays the effects on a model as the sequence is playing. With the window open, right click on the model name when on the sequencer tab and select Play model. It can also be opened/closed by clicking on the icon on the toolbar.

![](../../../.gitbook/assets/image%20%28493%29.png)

### ![](../../../.gitbook/assets/house-preview-icon.JPG) House Preview

The House Preview window displays the effects of your entire display where the model or model group has been assigned to the currently selected Preview window. Refer to explanations of multiple Preview windows in the Layout section. It can also be opened/closed by clicking on the icon on the toolbar.

![](../../../.gitbook/assets/image%20%28543%29.png)

### ![](../../../.gitbook/assets/effect-settings-icon.JPG) Effect Settings

The Effect Settings window displays the current or last effect that is being worked with. If an effect on the grid is selected or a new effect dragged to the grid, then this window gets updated with the ‘current’ effect.

![](../../../.gitbook/assets/image%20%28630%29.png)

Use the window to modify the attributes of the effect as required. The results of the change are displayed in the model window when selected and in the House Preview window when the sequence is played.

The Value Curves functionality in this window has been covered under a separate topic entitled Value Curves.

{% hint style="success" %}
It is possible to select a group of the same effects and change the settings of all of them all at once. For example you wish to increase 5 instances of the Circle effect to have the Number of Circles = 10. Select multiple instances of the effect by holding down control when you click on them. Change the Number of Circles setting to 10 , then click on the Update \(F5\) button in the Effect Settings window. The window can also be opened/closed by clicking on the icon in the toolbar.
{% endhint %}

### ![](../../../.gitbook/assets/color-picker-icon.JPG) Color

The Effect Colors window enables the user to change the colors of the current effect that is being worked with. If an effect on the grid is selected or a new effect dragged to the grid, then this window uses the ‘current’ color.

![](../../../.gitbook/assets/image-27.png)

Use the window to modify the colors of the effect as required. The results of the change are displayed in the model window when selected and in the House Preview window when the sequence is played.

The Value Curves functionality in this window has been covered under a separate topic entitled Value Curves

{% hint style="success" %}
It is possible to select a group of the same effect type and change the color of all of them all at once. For example 5, spiral effects that are all on different models and need to be changed to the same color. Select multiple effects by holding down control when you click on them. Change the color palette then hit the Update button beside the colors. The window can also be opened/closed by clicking on the icon in the toolbar.
{% endhint %}

By clicking on one of the colors, the color box will appear allowing you to choose or create any color you desire. To create a custom color, click on the Define Custom Colors &gt;&gt; button.

![](https://lh3.googleusercontent.com/UDBovR6ig4CcmmTSC67IE9Y3qFaGWzRRKZRy34S4T1mQ6_sc7SzWGSJ_7BABFFCZOoj82J7V6OoXPVpfMOTwAKtlYL6ImJvgh6oBOPs1J3sZj_huOK12obOwDp3gzI1BtlIiGfz1)

{% page-ref page="../../chapter-four-sequencer/changing-an-effect/changing-color-settings.md" %}

### ![](../../../.gitbook/assets/layer-blending-icon.JPG) Layer Blending

The first option of Morph is used with two or more layers. If selected, effect \#1 will morph/blend/fade into Effect \#2 midway through the timing interval in which the effects are placed.

![](../../../.gitbook/assets/image%20%28712%29.png)

{% page-ref page="../../chapter-four-sequencer/layers/layer-blending.md" %}

### ![](../../../.gitbook/assets/layer-settings-icon.JPG) Layer Settings

The Layer Settings menu has two tabs. The first tab \(Buffer\) defines how the effect will be adjusted during the render process in the buffer for the Model or Model Group. The second tab \(Roto-Zoom\) is used to apply the Roto-Zoom functionality to the model effect.

{% tabs %}
{% tab title="Buffer" %}
![](../../../.gitbook/assets/image%20%28681%29.png)
{% endtab %}

{% tab title="Roto-Zoom" %}
![](../../../.gitbook/assets/image%20%28587%29.png)
{% endtab %}
{% endtabs %}

{% page-ref page="../../chapter-four-sequencer/layers/layer-settings.md" %}

### ![](../../../.gitbook/assets/effects-icon.JPG) Effect Dropper

The Effects Dropper window displays all the supported effects and enables you to select a required effect and drag it to the sequence grid.

![](../../../.gitbook/assets/effects-window.JPG)

The same functionality can also be obtained using the effects from the effects toolbar as below:

![](../../../.gitbook/assets/effects-toolbar.JPG)

{% hint style="info" %}
The size on the icons on the Effects Toolbar can be adjusted by going to _Settings/Tool Icon Size._ There are 4 different sized icons are available for use.
{% endhint %}

### Value Curves

The Value Curves Dialog allows the user to drag and drop their saved values curves onto the desired effect setting.

![](../../../.gitbook/assets/image%20%28483%29.png)

### Color Dropper

The Color Dropper Dialog allows the user to drag and drop their saved colors/color curves onto the color palette.

![](../../../.gitbook/assets/image%20%28747%29.png)

### Effect Assist

The Effect Assist Window is an additional window that helps you determine how an effects is being drawn via a panel view.

![](../../../.gitbook/assets/image-749.png)

For example, if you open this window against a morph effect, the windows will display a grid corresponding to the x,y coordinates. If you then grab a slider for the morph effect and move it, the Effect Assist window shows exactly where the coordinate is being moved to, making it easier to determine what is being done to the effect.

You can also grab a corner of the image in the Effect Assist window and move it and have the slider values update in real time.

If you want single line morphs instead of area morphs then it's easier to just click with the left mouse button to establish the start points and click with the right mouse button to establish the endpoints. For areas you can either click and drag with either button or drag the handles.

### Select Effect

The Select Effects Window allows the user to select effects based on type, model, and time. Based on the Model, Time, and Effect selection, multiple effects can be selected and then bulk edit can be used to adjust the settings. This allows the user to, for example, select all the pinwheel effects on there mini trees and change the number of arms with bulk edit.

![](../../../.gitbook/assets/image%20%28160%29.png)

The search box allows the user to filter models with Regular Expressions\(Regex\). This allows the user to filter which models to select for selecting the effects. If you type in "MiniTree\*" for the search field it all the mini trees in the model list. The Model List allows the user to select which models to filter selection on. Only highlighted model names, will have their effects selected. The Time Fields allows the user to filter selection by time. The Effects List allows the user to filter effect selection by effect type.

### Video Preview

The Video Preview Window allows the user to preview the video file, they are using while sequencing it as the audio track.

![](../../../.gitbook/assets/image%20%2818%29.png)

### Jukebox

The Jukebox Window allows the user to "link" an effect or multiple effects to one of it's 50 buttons. These buttons can then be used for realtime playback i.e in a DJ or theater environment. This mapping can also be used by xFade.

![](../../../.gitbook/assets/image%20%284%29.png)

## Perspectives

The Perspectives Window enables you to save your current window positions and retrieve and use them later.

{% page-ref page="perspective-definition.md" %}

## Reset To Default

The Reset Toolbar option, when selected will reset the Windows and Toolbars to the default locations.This option should be used if you are missing an window or toolbar from the sequence window.

