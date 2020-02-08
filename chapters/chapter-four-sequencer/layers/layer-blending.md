# Layer Blending

## Layer Blending

![](../../../.gitbook/assets/image%20%28143%29.png)

The Layer Blendings window can be opened by clicking on the Layer Blendings icon from the toolbar or via the View , Windows menus.

![](../../../.gitbook/assets/image%20%28634%29.png)



#### Reset panel when changing effects

![](../../../.gitbook/assets/image%20%28251%29.png)

This will reset the Layer Setting back to default every time you select or create a new effect. Checked is the recommended setting for most users.

### Layer Blending

![Layer Blending Dropdown](../../../.gitbook/assets/image%20%2855%29.png)

When setting the layer blending modes, the current layer is considered layer 1 and the layer below is considered layer 2.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Layer Blending Modes</th>
      <th style="text-align:left">Layer Blending Mode Results</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Normal</td>
      <td style="text-align:left">Both layers will show, with layer 2 showing only where there is blank
        space from layer 1 as in thin spirals for example.</td>
    </tr>
    <tr>
      <td style="text-align:left">Effect 1</td>
      <td style="text-align:left">Ignore effect 2 and only show effect 1. Slide the slider to the right
        to blend in some Effect 2. Good for being able to hide an effect if you&#x2019;re
        not sure you want to use it.</td>
    </tr>
    <tr>
      <td style="text-align:left">Effect 2</td>
      <td style="text-align:left">Ignore effect 1 and only show effect 2. Slide the slider to the right
        to blend in some Effect 1.</td>
    </tr>
    <tr>
      <td style="text-align:left">1 is Mask</td>
      <td style="text-align:left">
        <p>Effect 2 will show wherever effect 1 is not showing.</p>
        <p>If E1=Fire, E2=Spirals, then the spirals would show on top of the fire,
          but the fire would appear to be black.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">2 is Mask</td>
      <td style="text-align:left">Same as effect 1, just reversed. Tip use Bars as the mask on layer 2 and
        you will have effect #1 reveal as if was coming from behind a curtain.</td>
    </tr>
    <tr>
      <td style="text-align:left">1 is Unmask</td>
      <td style="text-align:left">The non black areas of Effect 1 will be used to display Effect 2. Make
        Fire E1, Butterfly E2 and set both for 1 is Unmask. You&#x2019;ll see the
        awesome power of this blending mode. Black becomes white.</td>
    </tr>
    <tr>
      <td style="text-align:left">2 is Unmask</td>
      <td style="text-align:left">The non black areas of Effect 2 will be used to display Effect 1. Make
        Bars E1, Fire E2 and set both for 2 is Unmask. You&#x2019;ll see the awesome
        power of this blending mode. Black becomes white.</td>
    </tr>
    <tr>
      <td style="text-align:left">1 is True Unmask</td>
      <td style="text-align:left">Only allow Effect 2 to show through when Effect 1 has a non-black pixel.</td>
    </tr>
    <tr>
      <td style="text-align:left">2 is True Unmask</td>
      <td style="text-align:left">Only allow Effect 1 to show through when Effect 2 has a non-black pixel.</td>
    </tr>
    <tr>
      <td style="text-align:left">1 Reveals 2</td>
      <td style="text-align:left">Effect one will show on top of effect 2, except for areas in effect 1
        that are black. Effect 2 will show on the black areas of Effect 1.</td>
    </tr>
    <tr>
      <td style="text-align:left">2 Reveals 1</td>
      <td style="text-align:left">See 1 reveals 2. Same result, just transposed.</td>
    </tr>
    <tr>
      <td style="text-align:left">Shadow 1 on 2</td>
      <td style="text-align:left">The the layer 2 effect will show in the shape of layer 1. Try E1=Circles,
        E2=Butterfly to see what this does.</td>
    </tr>
    <tr>
      <td style="text-align:left">Shadow 2 on 1</td>
      <td style="text-align:left">Effect 2 will overlay on effect #1, where there is no black in effect
        #2.</td>
    </tr>
    <tr>
      <td style="text-align:left">Layered</td>
      <td style="text-align:left">Effect 1 only shows in black regions of Effect 2. Try Effect #1 as circles,
        E2=Bars with one of the colors as black</td>
    </tr>
    <tr>
      <td style="text-align:left">Average</td>
      <td style="text-align:left">Take value of Effect and Add it to Value from Effect 2. Average the sum.
        If E1 and E2 had yellow and blue circles, they would turn a dull green
        where the circles overlap.</td>
    </tr>
    <tr>
      <td style="text-align:left">Bottom Top</td>
      <td style="text-align:left">
        <p>Effect 2 will appear on the top half of the model.</p>
        <p>Effect 1 will appear on the bottom half of the model.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Left Right</td>
      <td style="text-align:left">
        <p>Effect 1 will appear on the left half of the model.</p>
        <p>Effect 2 will appear on the right half of the model.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Additive</td>
      <td style="text-align:left">Take value of Effect 1 and Add it to Value from Effect 2.</td>
    </tr>
    <tr>
      <td style="text-align:left">Subtractive</td>
      <td style="text-align:left">Take value of Effect 1 and Subtract it from the Value from Effect 2.</td>
    </tr>
    <tr>
      <td style="text-align:left">Max</td>
      <td style="text-align:left">Take the maximum value for each channel from both effects</td>
    </tr>
    <tr>
      <td style="text-align:left">Min</td>
      <td style="text-align:left">Take the minimum value for each channel from both effects</td>
    </tr>
  </tbody>
</table>{% hint style="success" %}
Put two effects on a model and step through each of the layering modes to see what they will look like. Experience is much better than reading about it.
{% endhint %}

<table>
  <thead>
    <tr>
      <th style="text-align:left">Layer Blending Samples</th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh4.googleusercontent.com/V8anpIiG1f5aYJ60kDHXNGLhglrgRmTyjTM3Wd3c5JCEY9dNEbmR2m7jrQeGhjZxTYKAyQHbhHSxfcxL20L7s8xRIdOT1st7LUJKjNLBGAjGDr0P8tErSN9NapyKVdUdvVKL5Px6"
          alt/>
        </p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh3.googleusercontent.com/sq_4VDV8u57kiPplEK0rYzk3MP_sbl7XD2C3g-27EQGxfUTiXa5euHLQho9Od1iDLfAucWNOpgNMP3GxfOOna2jOV2EYdotEuz4n5HIcJykWh4E2arCCMEkqHw1uWQMuTM6NPlj0"
          alt/>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh3.googleusercontent.com/TiwAhBSivOEGP__BypTtLI6Z-h7CIDfltjSPgO5zT3JMJQRun-Un9n1ZzfKUnXIQQxjOn98mFOxZx_hg7F0y1tAdW_YwYm2JAnKmFoaV6Hb1n305zB68dJtLqb-CGsQwEII_Z2rO"
          alt/>
        </p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh3.googleusercontent.com/3kMspsbKTrIoT5C07g050wlSP_HIX3LlcrD3OjGJAikyAToBQKoarq8ddfjAP1a5AzEg6q7RWRBSJmsqBP-0cgE8XL8oah7mrA6-j6cNHUBBK5MZeOztga1-0iuFeEirM70ScKuH"
          alt/>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh6.googleusercontent.com/8VqltNyiMNdMWdJ9jyiA8KO0CpuKyR_GEZoDMDUZjQWcU0Lt6YX3fcZdJeFsn3BMQt2S2iVW5pd5P2h4coQj4AfvCc8UkTJxMCq9ef8N2GfX9oA8AKCesTpBxdhoxUk22DU19qaS"
          alt/>
        </p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh3.googleusercontent.com/_3XMHX4fBN9nrSRO1xUp1Pb_07nP9I2pTyIWslOF_yX1uI1MVuMsgkCYyQIiFfrGzzAomcTHa2eTOzidsQQjeeZgsNfFR6_tekDyRAKkEaHuq15fLcbjTjJ2jYhvNuy0DFY_P4HL"
          alt/>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh4.googleusercontent.com/8LTkMkBO9AqpwK82ATLogim9HngDobt8GVbJSrz2Q5QiKasgF9_4RPzxo61ZWIbmHKngbkG353hAk1uee3CJTyvg7edIchztC2rcPdtVPEZuzyfFo58OEMtd8XhbMUriCxtmL_dC"
          alt/>
        </p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh6.googleusercontent.com/alwH3SKJi7U2v9j8gFA85DkVvaLYb34Up1xvNVswL2qho029hY6KbcrCPpuRGQYhJgBjAqwmixLrseDqEE9c6c-je0_bs4rCrjz3DE3qySu5DE6tGNOE6s9K6QUn_Oiy1m9GoCnt"
          alt/>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh4.googleusercontent.com/vI5xoCUy3qeAk7PRT4jPCCaB44CsaS0jkWyRFkPyq6ypXpID8scYE7uH9XByY9CcLdFMD4PFERqBeO5fo9Pu-WvdIw5CyCYxLa7dqlFdFR2eypJSP7-wNPxeKWqwWMGGxFlQUfjH"
          alt/>
        </p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh3.googleusercontent.com/mf1Cbrr0H1K1lHSLy9gvV-wrPx1yZw-t7jTC3C3mMYepNNPGwzWoCo1eyUHtLR5qC6tKinUE58YG2S3RD2b-nIENHgsGyty9r9_u_bpIPOu59UR8D7tHLKbS1M5fT1fGR3U08BLT"
          alt/>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh4.googleusercontent.com/rHcnDr4nh31fHVu9XducJLzyh2HLigOqboa5xhk3bTZCidiQIVX2FikfvqALwAe5Lx-ROeYyVEmWsjA_vpghk33fNGrW3yCyMgmVr8J0xSsWUMLp2KyMocDahCMm_i5G_-mFtAQB"
          alt/>
        </p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src="https://lh6.googleusercontent.com/FQSejW7lYIs-ryKDejCx4WcAT2SNuOyb5xp0XCUGAQZ8zH6pl8ovFGT5Qd4qx2up48dctGm2-abtKkxIcoNQLhyhhF8vGZh82n1UKq1emftL5zPXhHQ3dKKPhgcf1DWMKQ86Fiky"
          alt/>
        </p>
      </td>
    </tr>
  </tbody>
</table>### Layer Blending - Morph

This is not to be confused with the Morph Effect. This is a layering option that can be applied to any two effects.

![](../../../.gitbook/assets/image%20%28512%29.png)

The morph option of layer blending will magically make effect 1 ‘morph’ into effect 2 during the length of the timing cell that the effects are in. You will not see effect 2 at the beginning of the timing cell, and you will not see effect 1 at the end of the timing cell. Somewhere near the middle you will see the effect 1 ‘morph’ into effect 2.

### Layer Blending - Transitions

There are 13 layer blending transition choices. Using the transitions will help you bridge between effects providing a way to smooth out abrupt changes between different effects. A stylistic use would be between sections of a song such as the chorus to verse or verse to verse.  Keep in mind that the blending is done within the boundary of the timing mark and does not transition between timing marks.

![](../../../.gitbook/assets/image%20%28213%29.png)

 These transition choices are:

* Fade
* Wipe
* Clock
* From Middle
* Square Explode
* Circle Explode
* Blinds
* Blend
* Slide Checks
* Slide bars
* Fold
* Dissolve
* Circular Swirl

These transitions are common in the video editing world, and should be visually familiar to anyone who’s used video editing software or anyone who’s watched anything on TV in the past 20 years.

{% hint style="success" %}
When setting a layer transition, the setting will apply to all future effects placed, so be sure to reset the transition times back to 0 if you do not wish the transition to apply to all future effects.
{% endhint %}

* Clock - This uses a circular motion as the hand of a clock from the center of the model to wipe the effect in or out. The adjustment slider sets the starting position and the reverse checkbox allows for a counter clockwise wipe.
* From Middle  - This is a curtain type wipe either from the middle or towards the middle depending if the effect is placed on the in transition or the out transition.  The reverse makes the effect operate in a “to the middle” mode instead of “from the middle”. The adjustment slider will change the angle of the curtain direction.
* Square Explode - This transition will draw the effect starting from the middle of the model and expand outwards with square edges until the model is filled. The reverse button starts drawing the effect from the outer edges and filling in towards the middle.
* Circle Explode - Same as square explode, except the shape is circular instead of square.
* Blinds - This transition is analogous to twisting the wand to open vertical blinds.  The adjustment slider determines how many blinds are used. The reverse checkbox determines the direction that the effect will fill in from.
* Blend - This transition effect when used as an “in” transition rapidly fills the model with square chunks until the model is full. Likewise when used as the “out” transition, square chunks of the effect disappear until no pixels are left. The adjustment slider determines the size of the chunks.
* Slide Checks - This transition is a checkerboard type transition where the effect starts out with a checkerboard type of mask on the model and then the black portions are filled in either left to right depending on the reverse button selection. The size of the pattern  is set via the Adjustment slider.
* Slide Bars - This transition is broken up into 1-24 horizontal slices of the model determined by the Adjustment slider value. The effect selected will be filled in from opposite sides of the model interlacing each section until the model is filled. Slowly interlace your fingers with your palms facing you. That is how the effect looks on the model for the “in” transition.
* Fold - This transition bends the effect onto itself like a piece of paper.
* Dissolve - This transition will cause the effect to appear/disappear by adding/removing random pixels. 
* Circular Swirl - This transition will cause the effect to appear/disappear by emulating an object's rotation. 

If an effect has a transitions applied a green bar will appear for an in transitions and a red bar for an out transitions. If the in and out transitions overlap, the overlap area will appear yellow.

![](../../../.gitbook/assets/image%20%28573%29.png)

### Layer Blending - Mix Slider

This slider adjusts the level of each effect in the combined output of the effects. You can use this to just put a hint \(or more\) of one effect on another.

![](../../../.gitbook/assets/image%20%28149%29.png)

### Layer Blending - Canvas

![](../../../.gitbook/assets/image%20%28497%29.png)

Canvas Mode is a special render mode that only works with specific effects. The default render mode in xLights will draw the effects on a blank buffer for each layer. Canvas Mode allows an effect to draw on a previous layer without "blanking it" out. This is used by effects like the Warp and Kaleidoscope Effect that manipulate data from the underlying layers.

### Layer Blending - Canvas Layer

This Dialog allows the user which layers to use when Canvas Mode is Enabled 

![](../../../.gitbook/assets/image%20%28709%29.png)

![](../../../.gitbook/assets/image%20%28230%29.png)

