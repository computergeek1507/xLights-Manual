# Lighting Networks

## Lighting Networks

Each network should be defined, ensuring that the start and number of channels match the models in the layout tab.

{% hint style="info" %}
As described under [Quick Start Guide](../chapter-two-quick-start-guide/), you can start with a default set of configuration values and then come back to change or update the details before testing your lights physical output. Or you can chose to not define any network information at the beginning until you wish to test from within xLights.
{% endhint %}

### Add USB

USB Output type is used to define a DMX, Pixelnet, LOR dongle, D-Light, Renard or OpenDMX setup. Note: The LOR setting use a DMX style of channel numbering, the unit ID's are not used. Only the LOR optimized output type requires LOR unit ID's.

Each USB output type can be selected from the drop-down box. When a output type is selected, the text box below the drop-down will described the output type and how to configure it. The text can be used to identify the best choice for the USB dongle.

![](../../.gitbook/assets/image%20%28322%29.png)

### Add E1.31

Clicking on the Add E1.31 button will display the following dialog:

![](../../.gitbook/assets/image%20%28602%29.png)

Select the transmission method \(Multicast or Unicast\) depending on what option that will be used to drive individual lighting networks. If unsure, leave as Multicast. If Unicast is selected, then the IP address of the controller that will receive the universe\(s\) data must be defined. Enter the 'Starting Universe \#', '\# of Universes' and the 'Last channel' for each universe. The 'Last Channel, is the Universe Size. Most users use a size of 510 or 512. The 'One Output' checkbox allows for all these universes to be grouped together in the setup tab and only only take one line instead of one line per universe. This is the preferred method for most users. The Description attribute is useful for annotating what the particular channel range this network is controlling. Suppressing duplicate frames reduces network traffic if the data does not change. Priority is supported by some controllers and is used to determine which data packet to use is multiple packets are received controlling the same channels. Controller Type allows the user to specify the controller being used for controller upload and the controller visualize dialog. The 'Use Auto Start Channel checkbox, allows xLights to automatically set the start channels based on the controller connection. The FPP Proxy IP/Host option is used in conjunction with FPP 2.8+ Controller Proxy. This allows the user to setup a FPP device as a "tunnel" for their controller between the two network interfaces.

Press OK.

{% hint style="info" %}
If the ‘One Output’ is checked, then visually the universes and number of channels will be grouped as follows:
{% endhint %}

![](../../.gitbook/assets/image%20%28292%29.png)

The advantages of the 'One Output' option is less outputs in the Setup tab and the universes stay in numerical order. This can help avoided accidental dragging of the outputs. The disadvantage of this approach is individual universes cannot have different channel counts.

{% hint style="success" %}
Some controllers only support 510 channels per DMX universe. Check with your individual board and firmware version to see if 512 channels per universe is allowed. If configuring universes for a matrix that will be used on P10 panels and not using DDP, those universes should be defined as 512 channels per universe.
{% endhint %}

{% hint style="success" %}
If you have a number of contiguous universes of a fixed number of channels you can enter the starting Universe \#, a multiple of Universes and the Last Channel \(number of channels\), click OK and xLights will create the universes for you. You can then modify the details after that. Alternatively, define each Universe by specifying the Universe \# in the Starting Universe \# field, set the \# of Universes to 1 and set the Last Channel to the number of channels in that section of the Universe.
{% endhint %}

{% hint style="success" %}
When you save your setup, xLights also creates a ‘universes’ file which can be placed in the media folder on the Pi. This saves you having to enter all the controller config again.
{% endhint %}

The following picture shows a configuration where:

* Universe 1 has 94 channels from Channel number 1 to 94
* Universe 2 then has 460 channels from Channel number 95 to 554
* Universe 71 has 293 channels from Channel number 557 to 847
* Universe 5 then has 456 channels from Channel number 848 to 1303 etc.

![](https://lh5.googleusercontent.com/ZMrJZOYWqmyKGjFNgR0h9eLAzoHw9qwDEXX5iORskVo0gYB9eqlhDeYV7ZTt8iFIxCqupbzXUiotBViwoRHkNbJq8jrpFYSK9IAi9ICROu08ZWt79F3CaC-qZEO07YVLa9b9dQOH)

{% hint style="info" %}
If there are gaps in between, it is not required to specify the missing channels.
{% endhint %}

This image describes a setup where a LOR network has been listed first. Even though only the first 32 channels of the LOR network are used, universe 1 has been defined as 510 channels in case more items are to be added to the LOR network without impacting the other channels above.

![](../../.gitbook/assets/image%20%28222%29.png)

If output 1 is set to 32 channels, then output 2 will start from 33 on-wards - that is also a valid configuration.

### Add NULL

NULL output type is used to generate channel blocks with no physical hardware or controller. This type of output is used in setups, where the sequence output will not be used by xLights as a show player, but output data to be used for playback on a Raspberry Pi or BeagleBone Black controller.

There could be large matrices to be implemented via P10 or P5 panels running off a BeagleBone Black controller. A null output can reserve a huge number of channels, but not actually output anything if the Output to Lights function is on. A model can still be sequenced as normal and viewed on all the windows just as any other output.

Click on Add Null and specify the number of channels to be reserved. The corresponding number of channels will be created.

{% hint style="info" %}
If the Falcon Player on the Raspberry Pi or BeagleBone Black controller is to be used in ‘Bridge Mode’ \(for testing via the sequencer prior to your show\) then the corresponding channels must be defined. It is recommended to use a DDP Output for this. If a definition of NULL is used no data will output to any lights.
{% endhint %}

### Add ArtNET

Clicking Add ArtNET will display the following dialog:

![](../../.gitbook/assets/image%20%28709%29.png)

Specify the IP Address of the controller board, there are 2 ways of defining universes. If the IP address is known, use the Net/Subnet/Universe tab, if the IP address is not known use Universe only. Specify the number of universes that output will receive and the number of channels per universe. Optionally enter a description for this ArtNet output.

Press OK.

### Add LOR \(Optimized\)

Clicking the LOR button will bring up the following dialog:

![](../../.gitbook/assets/image%20%28737%29.png)

LOR \(Optimized\) is much closer to true LOR protocol and utilizes some of the more advanced commands. First, set an ID of the ouput, this is **not** the unit ID of a controller box, it is a unique ID that xLights will use to direct the channel data to this output. The port is the COM port of the dongle in use, Baud Rate is adjustable. NOTE: Older black or white LOR dongles do not support speeds over 115200, Only the red LOR dongle will support higher speeds. Description is user defined value to identify the output. The Controller Table displays the list of LOR controller. Each controller will be listed by controller type, Unit ID, Number of Channels, and Address Mode. Select the "Add" Button to add a new LOR controller. Finally a box that you add the controller ID's that you have each controller set up to. Note: xLights cannot set the unit ID to the controller, this must be done via the LOR software or from the DIP switches on the controller board if applicable.

When adding a LOR controller the following dialog will appear:

![](../../.gitbook/assets/image%20%28481%29.png)

Select the LOR controller type, the available choices are: AC Controller, RGB controller, CCR, CCB, and the 3 Pixie Controllers \(4 ,8, 16 output boards\). Then select the number of channels for this controller board. Next is the unit ID. This can be very confusing as LOR uses a hexadecimal system for numbering their UNIT ID's. Units 1 to 16 are 01-0f and units 17-32 are 11-1f. A lot of LOR users will number their boxes 01-09 then 11-19 and so on. Make sure the hex number in bold matches the LOR unit ID in their software. Set the addressing mode as normal, legacy, and split. A description for each controller can be provided.

Click Ok after each controller ID is set.

Click Ok when done adding all unit ID's to finish the LOR Optimized network setup.

### Add DDP

Selecting DDP will bring up the following dialog:

![](../../.gitbook/assets/image%20%28765%29.png)

DDP \(Distributed Display Protocol\) is a high efficiency data protocol. It is more efficiency than ArtNET or E.131. Currently, this protocol is not supported by all Ethernet based controllers. \(only Easylights, FPP 2.x+, and Minleon\) It is most useful to send large data packets to FPP for controlling P10 and P5 matrix's. It uses absolute channel addressing. IP address is the controller IP, The ID should be unique number that is not an already used universe number or the ID of another network. The number of channels is the total number of channels that the controller is using. NOTE: a P10 panel is 1536 channels for each panel and a P5 is 6144 channels for each panel. The channels per packet should be left to the default of 1440. Checking the box to keep channel numbers, this sends the channel numbers to the controller. If left unchecked the first channel in DDP will be channel 1. Description is a user field to identify this DDP network. Suppressing duplicate frames reduces network traffic if the data does not change. Controller Type allows the user to specify the controller type to use for controller upload and controller visualize dialog.The 'Use Auto Start Channel checkbox, allows xLights to automatically set the start channels based on the controller connection. Autosize output allows xLights to automatically determine the number of channels needed based your model settings and resize the channel count for you. The FPP Proxy IP/Host option is used in conjunction with FPP 2.8+ Controller Proxy. This allows the user to setup a FPP device as a "tunnel" for their controller between the two network interfaces.

Click OK

### Add ZCPP

Selecting ZCPP will bring up the following dialog:

![](../../.gitbook/assets/image%20%28277%29.png)

ZCPP \(Zero Configuration Pixel Protocol\) is a high efficiency specific data protocol with build in configuration data for the controller outputs. It was designed to automatically configure the controller outputs in real time. It also supports a discover interface, so xLights can automatically find the controllers on your network. It is more efficiency than ArtNET or E.131. Currently, this protocol is not supported by all Ethernet/Wifi based controllers. \(only Falcons FW 2.5+ and ESPixelStick based controllers\) It uses absolute channel addressing. IP address is the controller IP address or host name. The number of channels is the total number of channels that the controller is using. Description is a user field to identify this ZCPP network. If the controller was auto discover, this should be the description/host name provided by the controller. Suppressing duplicate frames reduces network traffic if the data does not change. Autosize output allows xLights to automatically determine the number of channels needed based your model settings and resize the channel count for you. Support Virtual Strings is a feature that the ZCPP controller must support. It allows a single pixel string output to have different settings per model. The Falcon Controllers support there feature. Support Smart Remotes is another feature that the ZCPP controller must support. Smart Remotes are a smart differential receiver board supported by the Falcon controllers. Multicast allows the ZCPP output to use Multicast network traffic instead of the default, Unicast. Suppress sending configuration will prevent the ZCPP output from sending the controller configuration packets and only sent the pixel data packets. Priority is supported by some controllers and is used to determine which data packet to use is multiple packets are received controlling the same channels.

Click OK

### Change, Delete or Delete All

To change or delete an individual row, highlight the row and select Change or Delete. Click on Delete All to delete the entire set up.

### Discovery

This will automatically find ZCPP and DDP controllers already attached to your local network.

### Save Setup

Once you have your lighting network setup, clicking on Save Setup will save your configuration. After any changes are made to the Setup tab the Save Setup button will light red to identify there are unsaved changes.

{% hint style="success" %}
After you have at least one output defined you can use the Right Click in the output area to bring up a popup box with several functions on it.
{% endhint %}

### Right Click popup

![Right Click Menu](../../.gitbook/assets/image%20%28508%29.png)

Upload To Controller has three sub-menus choices 'Upload to All Controllers', 'E1.31 Input Definition', and 'Output'

![](../../.gitbook/assets/image%20%28235%29.png)

#### Upload to all controllers

This is used to upload E1.31 Input and Output definitions to all Ethernet based controllers defined by the layout tab. Only Outputs Types with IP specific addresses defined will be uploaded to the controller.

{% hint style="info" %}
E1.31 Input Definition's are only require for E1.31 or ArtNET controllers. i.e FPP, Falcon, and SanDevices. Output Definition's are required for all controllers types.
{% endhint %}

#### E1.31 Input Definition

This requires a valid IP address E1.31 outputs specified as multicast cannot use these features. The E1.31 Input Definition's will only be preformed for the IP address selected \(the line you right clicked on\). This function will not work for multicast. The following choices are given:

#### FPP Bridge Mode

This is used to quickly upload the input controller configuration for a FPP in Bridge mode running pixels using a PiHat or RGBCape or similar. If you do not have a FPP nor PiHat or RGBCape then do not use this.

#### Falcon

This is used to upload the input E1.31 definition to a falcon board. This will copy your xLights output for all E1.31 defined to this IP address in setup tab and make it the input on the falcon board. This will overwrite any previous setup on the falcon board so do use caution.

#### SanDevice

This is used to upload the input E1.31 definition to a SanDevice board. This will copy your xLights output for all E1.31 defined to this IP address in setup tab and make it the input on the SanDevice board. This will overwrite any previous setup on the SanDevice board so do use caution.

#### Output

This uses the parameters from models in the Layout tab, utilizing controller connection on each model. This feature is available for the following boards : Falcon, Pixlite/Pixcon, SanDevices, J1SYS, AlphaPix, HinksPix, Espixelstick, and most FPP caps and capes. This feature is compatible with both universe/channel addressing and absolute addressing.

{% hint style="info" %}
You can have a model span multiple outputs, or you can have multiple models on one output. The upload function will work on most standard layouts.
{% endhint %}

#### Insert After

Insert After you to insert additional outputs after the output selected but before the next output already defined.

It has the same choices from the left side buttons, USB, E1.31, NULL, and ArtNet. The add box will look identical to the add using the buttons on the left.

#### Bulk Edit

Bulk Edit allows you to change a group of outputs making one change and applying it to all of them. This is very handy in where a mistype of an IP address can be corrected very easily. It has choices of IP Address, channels, and description and suppress duplicate frames.

#### Delete

This will delete the highlighted outputs.

#### Activate / Deactivate

These toggle the "Enable" value. The Enable value turns on/off that output when "Output to lights" is turned on. If it's not enabled, no output occurs. For example, if you have a controller not plugged in \(testing a different controller\) disabling that output would not attempt to send anything to that specific controller. Trying to send data to a controller that is not connected and in some cases cause delays and lags on the output. When an output is disabled the row will be lightened to show that it is not enabled.

![](../../.gitbook/assets/image%20%28466%29.png)

#### Open Controller

Open the currently selected IP address in your default web browser.

#### Ping Controller

Ping the currently selected IP address and wait for an acknowledgment from the device.

#### Visualize Controller‌ <a id="visualize-controller"></a>

If the Controller Type is Specified this option will appear and allow the user to view the controller connections.‌

{% hint style="danger" %}
If a controller type is not set the Visualize Controller‌ option will not appear.
{% endhint %}

![](../../.gitbook/assets/image%20%28556%29.png)

There is also a right click menu to print the controller connections or Save as a CSV file.

![](../../.gitbook/assets/image%20%28180%29.png)

