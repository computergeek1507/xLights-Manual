# Model Settings

### **Model Settings**

![](../../../../.gitbook/assets/image%20%28127%29.png)

### **Name**

The name of the model. The Model name can be changed by clicking on the existing name and changing to a new value.

###  \# Strings

The \# of Strings corresponds to the physical number of strings for that model and is generally 1.

### **Nodes/String**

Nodes per String denotes the number of nodes/pixels per string. If your model has 2 strings and 50 node per string, the total number of nodes is 100.

### **Lights/Node**

Lights per Node denotes the number of physical lights per node. \(i.e. for pixel strips with 3 LEDs per controller chip, this would be 3\).

### **Lights/String**

{% hint style="info" %}
### **Only available when the 3/4 Channel RGB Selected or Single Color string type is selected.**
{% endhint %}

Lights per String denotes the number of lights per string. This will be used instead of the Nodes/String and Lights/Node settings.

### Start Location

Location of the first pixel or first channel location. "Green Square" means the starting location is the green square on the layout and "Blue Square" means the starting location is the blue square.

### Start Channel

The Start Channel corresponds to the starting channel of the first node for the model. xLights will automatically calculate the end channel based on the model settings.  

By Default, xLights will "chain" all you models together, this means the start channels will just follow the previously model.

In this example, the Start Channel has been set to start immediately after the ‘Candy Canes-2’ model.

![](https://lh5.googleusercontent.com/XTqp-MvwBYHO1_UVBJz0w4BF_bZzs6tm4h-_l3onh4F9iLQAMkCCQ9uo2Cf8ZIfoFCuC5THNfHRNC1mO781eTquTElOwFOw2pYUL0JVGbZ1SU402fChgRE3lmoTOlyfni2H3TNOO)

xLights will automatically calculate the start channel and end channels, and if the ‘Candy Canes-2’ model’s channels change, then the start and end channels for this model will automatically be recalculated.

### Individual Start Channels

For models with multiple strands or elements, you can specify the start channel for each strand individually if required. This is useful where the channel numbering is not contiguous.

![](https://lh4.googleusercontent.com/_XIuO-mmrRTqKWRHhlaEVEfSEWlqRdgRsQ0THmg64b6lIJsV4hrop8zyNTtIddqyKuCwPwIHaBhvWEPuRr5filiQk4tknU0bHvZdMkbicrrSBEUJ8vHEwsCLLB5uyfNEJhZZ2a1Z)

\*\*\*\*

### Preview Display 

The Preview setting controls whether the model is to appear in the House Preview screen and also which Preview layout screen. Click within the setting to open up a window which lists all the available Previews. If you have created additional Preview layouts, they will be listed in the window.

The ‘Default’ value represents the default preview window.

![](https://lh4.googleusercontent.com/3-iiyZ5wxCRs7TcRliAl_gsZEvSyjt1DaRyquybWhdKM0B6NEWSfHfSYgpsphKArPyNCdICcfenK2pmfkDXuDzi4Wcm77-xVbnJDFEujKI1V7HK36y5F4ltTJcZNHoMRVOkvLCTI)

‘All Previews’ indicates that the Model is to be displayed in all Preview Windows.

‘Unassigned’ indicates that the model will not be displayed as it is not assigned to a Preview window

‘Unassigned’ is sometimes useful where the same physical item has been re-defined using more than one model definition for ease of programming the effects. One of them should have the Preview set to ‘Unassigned’ and the other should not.

The ‘2nd Preview’ is one that has been user created.

{% hint style="info" %}
There are 4 rules to determine if a model shows up on a Preview.

The model is assigned to the Preview.

1. The model is assigned to All Previews.
2. The model is a member of a model group that is assigned to the Preview.
3. The model is a member of a model group that is assigned to All Previews.
{% endhint %}

### **Strand / Node Names**

![](https://lh6.googleusercontent.com/XMPoMja7F3rEsUmo05NOV5o-YE3AuUBsRbR7uYvPiAXJ577aG7XHMetDJwfBzyElRgt9V1FRJO1JvCHbPwjNm5CtQVm1xkpz9n5vbARvS5Hz3OX1EakHOxtbOP9QX-npTlGpfSLa)

Each strand and node can have a name assigned to it.  This is useful where for example you have single channel models that are grouped together \(singing faces, tombstones or DMX props etc\). On the sequencer, double clicking on the strand reveals the nodes with meaningful names against them.

### Faces

This setting is used to specify the Faces definition for custom models that support Singing faces.

Functionality has been covered in the Singing Faces section.

{% page-ref page="../../../chapter-four-sequencer/singing-faces/" %}

### Dimming Curves

The Dimming Curves setting can be used to change/reduce the brightness of the lights for a specific model.  The intensity of the lights is accordingly changed/reduced from its default value of 100%. Use the "Brightness" slider where you can reduce \(or increase, but 99% of the time, you reduce\) the brightness of the model in the FSEQ. Change the gamma curve of each of the red, blue or green values.

You can select from the options to have a single gamma value or change individual gamma values. You can also select the values from a file, in which case you are prompted for the location of the file.

![](https://lh5.googleusercontent.com/rwLWwriqGZO32hMS7xnRQhJT8Rv-HHK-VsldJpXxAz1yIDcopyaA_cI_FNqtySGinC3vwVhXPDc9j5Jfim7BVg03yqCvmB6QKAJfN0Ebw-fx-ij0CjlUg_RXCd1-MaNlsPjxGwBA)

| **Color** | RGB Values |
| :--- | :--- |
| Orange | R:255 G:37 B:0 |
| Orange | R:255 G:48 B:0 |
| Darker Orange | R:255 G:29 B:0 |
| Hot Pink | R:255 G:0 B:93 |
| Turquoise | R:8 G:255 B:143 |
| Congo Blue | R:33 G:0 B:148 |
| J. Winter Blue | R:0 G:0 B:140 |
| Jade | R:0 G:181 B:165 |
| JAS Green | R:86 G:222 B:0 |
| Med Yellow | R:255 G:247 B:0 |
| Oklahoma Yellow | R:255 G:211 B:0 |
| Bastard Pink | R:255 G:115 B:107 |
| Grass Green | R:0 G:109 B:44 |
| Royal Purple | R:40 G:0 B:123 |

{% hint style="info" %}
It helps when all of your LEDs have the same wavelength of colors in them. If one set has a darker red or blue you'll get different colors out of those on the same values.
{% endhint %}

### **State**

This setting is used to specify the State definition for custom models that support Singing faces and Coro Tuine to signs.  Functionality has been covered in the State Effect section.

### Sub-Models

This setting is used to specify parts of a model to be controlled as if it were its own model. This is used for example if you have a wire frame with 2 arm positions you then can sub model those and control them without the need for adding a 2nd or 3rd model.

![Submodel Dialog](../../../../.gitbook/assets/image%20%28645%29.png)

You will find the sub-model listed as parent model name/sub model name. This can be added to groupings and added to sequencing as a stand alone model. 

See the Sub-Models Section for more info.

{% page-ref page="../../sub-models.md" %}

### **Controller connection**

This setting is used to specify which output of the controller is being used by this model. Right now the only boards currently working are falcon boards. Protocol is the pixel type. Port is the output number on the controller board.

![](https://lh4.googleusercontent.com/R1Pe6LjDofDItrSuJOySLqkUECJvq6imrwAP7TWk3FTSOKn6UIfAFsVg2viImvUF0X0feesiWGz-hPY9yTU_G8xU9JM_ea0BZcS0J9vn1eMnHrKdslOny2cRolh4BpW61YEKJFNG)

How this is used is covered under setup tab.

### String properties

The String Type enables you to set or change the ‘RGB’ orientation of your nodes.

The first six options in the list below are used for Pixels  - these can also be set in the hardware controller. Dumb pixels are set to either 3 Channel RGB or 4 channel RGB and single “A/C” or store bought fairy lights are set to single channel.

![](https://lh6.googleusercontent.com/3HNiKjGn2RmEAfZsWlg_U60v1SQDDcwIM9cdkEzUpVZRxlC6L2nvt6J2bSxc3GGy81oEcnbDNY0CRpOkvknWNj_EAeQgxVULCVD_3JkMeU0MfTBLmGFTkFx7L813UpnLnSMxH9ZQ)

The Color setting is used for Single Color string types to

define which color the string responds to. If set to White , then only when the White is on, on the sequence , will it light. If set to say Red , then it will light if Red is on \(which is 255,0,0\) or if White is on \(because White sets 255,255,255 on\).

### Appearance

The Appearance setting is used to determine how a particular element is displayed when viewed in the Layout, House Preview and Model windows. By increasing the Pixel Size, the appearance of the element  \(a flood or any other small element\) can be made to display a bigger size. The Transparency and Black Transparency values can be used to adjust how opaque or transparent the element is on the display.

![](https://lh6.googleusercontent.com/CdX3TIPuM6xa7V6FHSA5CylM5E0xlmfw8tSVoaPNNhWnqx5fpGxc0mmPvCzhL2naI5cH_xZZX4-DDRz7z4pGzFJgBOiAwzqidt-NcVIS_S3cfKNdUz0Y3jB7aAuMBKyVVk_LlLRC)

### **Size/Location**

The size/location settings describes where on the Layout screen a model has been place, and its  relative size to the model grid.

![](https://lh3.googleusercontent.com/ep6ZJt4I50jzAAFdjBwFiAj09vnWZAuMyzLbDeGYVwj34tDqm3tysL-kwDOvm50lAGxsls885UGd3sxnoLRQ3VSvZnHjDdPzqLw4Xrw3_OPDOGBHsiCjfetw-RezSLQnKKXU77ZR)

It auto adjusts as you move or adjust the size and orientation of the model image and normally does  not have to be manually set or adjusted.

{% hint style="success" %}
In the event that the model has ‘disappeared’ from the screen or has shrunk  or is hidden behind another model, then adjusting these values to a larger value can help to locate the model after which the model image can be adjusted as usual.
{% endhint %}

