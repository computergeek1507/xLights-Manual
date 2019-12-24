# Changing Start Chanel

### **Changing Start Chanel**

Click within the Start Channel cell and then click on the highlighted box to open up The Start Chanel Window.  

![](https://lh5.googleusercontent.com/encWdVPmtrdMw4yOeiL7VLjkFYI2EcFC_pw0RYbWhhZkFr12gpzdPxIWs2zyVCijzawqcShaAAX1c1Xn4GSVEKzRD9nCeD66Y1E1Z7NIM1ZfeAQrf3Rk5V9DAjYyPOyIvqmXrtBC)

The From Output in most cases is set to 1 as default and the start channel is then used to define the absolute channel number. 

However it is possible to use other definition setups:

Click within the Start Channel cell and then click on the highlighted box to open up a secondary window.  

If you select the ‘Output Number’ option, the start channel for the model is calculated based on the “start channel” that is offset from this ‘From Output’ number \(default is 1\).  The Output number refers to the row on the Setup tab.

If you have 4 outputs setup on your setup tab being universes 10 through 14, all with 510 channels, for the model set as Start Channel “1”, Output Number “2”, its real start channel in the fseq would be channel 511  \(first channel of the second output\). But the universe would be 11 \(as that is on the second row i.e Output 2 of the set-up tab\), not Universe 2.

If you select the ‘Universe Number’ option, the start channel for the model is calculated based on the “start channel” that is offset from this ‘Universe Number’ \).

If you have 4 outputs setup on your setup tab being universes 10 through 14, all with 510 channels, for the model set as Start Channel “1”, From Universe “11”, its real start channel in the fseq would be channel 511  \(first channel of the Universe 11\).

The “ANY” value indicates that the Universe is not specific to an IP address and therefore xLights searches for the universe number. \(This is the recomended setting to use\)

You can specify a specific IP address if you wish - in the unusual event that you have the same universes on different controllers on different IP addresses.   

The start channel value can also be specified relative to other channels using the End of Model or Start of Model options. You can specify an offset from an output number or select the start channel to start from the end of another model or align with the start of another model \(in the last two scenarios, the model name  is to be selected from a drop down box\).

This options works well if your models are reasonably static as the channel numbers are automatically calculated. If however, you delete models then it can break the chain . xLights will alert you to this , but the popup dialogs could be tricky to navigate through.

