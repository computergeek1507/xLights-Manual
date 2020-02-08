# Video

![Icon](../../.gitbook/assets/image%20%28282%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28367%29.png)

![](../../.gitbook/assets/image%20%28606%29.png)

The Video effect enables a video media file to be selected and directly played as a video clip sequence.  A video file that will be used for the effect. Supported file types are \*.mp4, \*.mpg, \*.avi, \*.mov, \*.flv, \*.mkv and \*.asf files.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Option/Settings</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Video Location</b>
      </td>
      <td style="text-align:left">Identifies the name and location of the video file to be played.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Start Time</b>
      </td>
      <td style="text-align:left">Defines the point in the video at which the effect should start playing.
        The default is to start from the beginning.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Duration</b>
      </td>
      <td style="text-align:left">Length of the video file.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Duration Treatment</b>
      </td>
      <td style="text-align:left">
        <p>&quot;Normal&quot;, &quot;Normal No Blue&quot;, &quot;Loop&quot; , &quot;Slow/Accelerate&quot;,
          &quot;Manual&quot;, &quot;Manual and Loop&quot;.</p>
        <p></p>
        <p>&quot;Normal&quot; will play the video once for the duration specified.
          If the length of the video is less than the duration, the effect will appear
          blue until the end duration.</p>
        <p></p>
        <p>&quot;Normal No Blue&quot; will play the video once for the duration specified.
          If the length of the video is less than the duration, the effect will appear
          blank until the end duration.</p>
        <p></p>
        <p>&quot;Loop&quot; will loop to the beginning and play the video again if
          it ends before the duration of the effect.</p>
        <p></p>
        <p>&quot;Slow/Accelerate&quot; will adjust the video speed to fit the duration.</p>
        <p></p>
        <p>&quot;Manual&quot; allows you to manually set the video length with the
          duration text box.</p>
        <p></p>
        <p>&quot;Manual and Loop&quot; allows you to manually set the video length
          with the duration text box and then will loop the video.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Speed</b>
      </td>
      <td style="text-align:left">Speed up the video speed.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Maintain Aspect Ration</b>
      </td>
      <td style="text-align:left">If selected , then the video aspect ratio (16:9 or 4:3) will be used,
        else the effect will attempt to change the aspect ratio to better match
        the model dimensions.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Use sequence audio file as video file and synchronize</b>
      </td>
      <td style="text-align:left">If using a video file as the sequence audio track, this options will use
        this file to display the video.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Crop</b>
      </td>
      <td style="text-align:left">Trim the size of the video&apos;s resolution.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Transparent Black</b>
      </td>
      <td style="text-align:left">Allow black pixels to be transparent. Slider adjust at what level &quot;black&quot;
        becomes transparent.</td>
    </tr>
  </tbody>
</table>The video duration is adjusted to fit the time that is selected for the duration effect. If the video duration is shorter than the time selected, then the video will loop to fit the duration.

{% hint style="danger" %}
If you move the image that you have used for the video effect to a different location or delete it, when you next run the sequencer, if the image is not found, an error message will not be displayed, but the effect will render a blank image. The only time this won’t happen is if only the drive letter has changed,  and the rest of the path is the same.
{% endhint %}

{% hint style="warning" %}
If the Video Effect is appearing as a "Red" video, the video effect cannot find the video file.
{% endhint %}

