# Pictures

![Icon](../../.gitbook/assets/image%20%28783%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28684%29.png)

{% tabs %}
{% tab title="Start Position" %}


![](../../.gitbook/assets/image%20%28427%29.png)
{% endtab %}

{% tab title="End Position" %}


![](../../.gitbook/assets/image%20%28322%29.png)
{% endtab %}

{% tab title="Start Scale" %}


![](../../.gitbook/assets/image%20%28777%29.png)
{% endtab %}

{% tab title="End Scale" %}


![](../../.gitbook/assets/image%20%28167%29.png)
{% endtab %}
{% endtabs %}

The Pictures effect is used to import a supported image type \(gif, bmp, jpg etc\) and render that image as an effect while also allowing the image to be manipulated and edited within xLights.  You will need a image that is to be imported.  Save the image as a GIF file and make the background color transparent if you don’t want the original \(white\) background of the image.

Place the Picture effect in on timing cells that you wish to have the effect on a model.  Click on the effect on the grid and amend the parameters as required. First click on the Browse button and navigate to the location of your image, select the image and click open or double click to select the image.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Option/Settings</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Movement</b>
      </td>
      <td style="text-align:left">
        <p>Controls how the image will move across the model layout.</p>
        <p>In addition to directional options such as left, right, wiggle etc, there
          are a number of special options, such as peekaboo, flag wave.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Movement Speed</b>
      </td>
      <td style="text-align:left">Controls how fast the image moves across within the effect timeframe.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Frame Rate Adj</b>
      </td>
      <td style="text-align:left">When using the pictures effect to play an GIF, this setting is used to
        set the playback speed if needed to speed up or slow down the playback.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Offset in Pixels</b>
      </td>
      <td style="text-align:left">Used to specify exact number of pixels rather than % for the start and
        end positions offset.</td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">
        <p>&quot;No Scaling&quot; Image file will not be resize and excess pixels
          will be chopped off.</p>
        <p></p>
        <p>&quot;Scale to Fit&quot; Image file will be resize to your model. Vertical
          and horizontal dimension will be scaled independently.</p>
        <p></p>
        <p>&quot;Scale Keep Aspect Ratio&quot; Image file will be resize to your
          model but the dimension are scaled together to keep the original aspect
          ratio.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shimmer</b>
      </td>
      <td style="text-align:left">Fade in and out random pixels in the image.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Loop Animated GIF</b>
      </td>
      <td style="text-align:left">Replay GIF animation, if GIF is shorter than effect length.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Suppress GIF Background</b>
      </td>
      <td style="text-align:left">Remove GIF background color and make it transparent.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Transparent Black</b>
      </td>
      <td style="text-align:left">Allow black pixel to be transparent. Slider adjust at what level &quot;black&quot;
        becomes transparent.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Start Position: (x,y)</b>
      </td>
      <td style="text-align:left">Sets the position of the image if it does not need to be centered on the
        model.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Start Position: (wrap x)</b>
      </td>
      <td style="text-align:left">Used to bound the picture image within the model. Defines and controls
        the coordinates of the &#x2018;bottom left&#x2019; start corner.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>End Position: (x,y)</b>
      </td>
      <td style="text-align:left">Used to bound the picture image within the model. Defines and controls
        the coordinates of the &#x2018;top right&#x2019; end corner.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Start Scale</b>
      </td>
      <td style="text-align:left">Set the starting position scale (0 - 1000%) independently of the start
        position.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>End Scale</b>
      </td>
      <td style="text-align:left">Set the ending position scale (0 - 1000%) independently of the end position.</td>
    </tr>
  </tbody>
</table>{% hint style="success" %}
The playback rate is influenced by the length of the effect.  So if you change the time length of your effect and have an image that is non stationary, the rate of movement will adjust according to the new time length.
{% endhint %}

{% hint style="danger" %}
If you move the image that you have used for the picture effect to a different location or delete it, when you next run the sequencer, if the image is not found, an error message will not be displayed, but the picture effect will render a blank image. The only time this won’t happen is if only the drive letter has changed, and the rest of the path is the same.
{% endhint %}

