# Lighting Networks

## Lighting Networks

{% hint style="info" %}
**You can skip this section if you have not have hardware yet, and do not plan to output data to your lights.**
{% endhint %}

The Lighting Networks section defines how the channels are mapped to physical lighting hardware and controllers. It is only used when outputting data to the controllers and can easily be changed at any time.

You do not have to define any network when you start , but you will need it defined before you can test any effects on physical lights from within xLights.

If you do want to define the network details at this stage, select the Setup tab and define a default network. The actual network does not have to be correct as you can change the details later without impact to other components.

You can click Add Null and define a block of say 10,000 channels to work with \(ensure that this is larger than what you will have in all your models\) or you can define them as E1.31 which is the most common type.

Click on the Add E131 button:

![](../../.gitbook/assets/image%20%28553%29.png)

Select Multicast, Starting Universe \# = 1, \# of Universes = 20, Check "One Output", Last Channel = 512, and press OK. The Description filed can be left blank at this stage.

![](../../.gitbook/assets/image%20%28296%29.png)

This will create a single output with 20 universes. Each universe will have 512 channels. The start and end channel are automatically calculated and displayed in the mapping column.

Click on Save Setup to save the network created.

![](../../.gitbook/assets/image%20%28556%29.png)

