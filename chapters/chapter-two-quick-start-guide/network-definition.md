# Network definition

## **Network definition**

{% hint style="info" %}
**You can skip this section if you have not have hardware yet, and do not plan to output data to your lights.**
{% endhint %}

The network definition section defines the Universes that you will use and the channels within each universe. It is only used when outputting data to the controllers and can easily be changed at any time.

You do not have to define any network when you start , but you will need it defined before you can test any effects on  physical lights from within xLights.

If you do want to define  the network details at this stage, select the Setup tab and define a default network.  The actual network does not have to be correct as you can change the details later without impact to other components.

You can click Add Null and define a block of say 10,000 channels to work with \(ensure that this is larger than what you will have in all your models\) or you can define them as E1.31 which is the most common type.

Click on the Add E131 button:

![](../../.gitbook/assets/image%20%28464%29.png)

Select Multicast,

Starting Universe \# = 1,

\#of Universes = 20,

Last Channel = 512,

and press OK.

The Description filed can be left blank at this stage.

![Setup E131 Dialog ](../../.gitbook/assets/image%20%28608%29.png)

This will create 20 universes, each of 512 channels starting from Universe 1 to Universe 20.  The start and end channels are automatically calculated and displayed in the last column.

Click on Save Setup to save the network created.

![](../../.gitbook/assets/image%20%2895%29.png)



