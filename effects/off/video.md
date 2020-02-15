# Video

![Icon](../../.gitbook/assets/image%20%28339%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28429%29.png)

![](../../.gitbook/assets/image%20%28695%29.png)

The Video effect enables a video media file to be selected and directly played as a video clip sequence. A video file that will be used for the effect. Supported file types are \*.mp4, \*.mpg, \*.avi, \*.mov, \*.flv, \*.mkv and \*.asf files.

| Option/Settings | Description |
| :--- | :--- |


| **Video Location** | Identifies the name and location of the video file to be played. |
| :--- | :--- |


| **Start Time** | Defines the point in the video at which the effect should start playing. The default is to start from the beginning. |
| :--- | :--- |


| **Duration** | Length of the video file. |
| :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Duration Treatment</b>
      </th>
      <th style="text-align:left">
        <p>&quot;Normal&quot;, &quot;Normal No Blue&quot;, &quot;Loop&quot; , &quot;Slow/Accelerate&quot;,
          &quot;Manual&quot;, &quot;Manual and Loop&quot;.</p>
        <p>&quot;Normal&quot; will play the video once for the duration specified.
          If the length of the video is less than the duration, the effect will appear
          blue until the end duration.</p>
        <p>&quot;Normal No Blue&quot; will play the video once for the duration specified.
          If the length of the video is less than the duration, the effect will appear
          blank until the end duration.</p>
        <p>&quot;Loop&quot; will loop to the beginning and play the video again if
          it ends before the duration of the effect.</p>
        <p>&quot;Slow/Accelerate&quot; will adjust the video speed to fit the duration.</p>
        <p>&quot;Manual&quot; allows you to manually set the video length with the
          duration text box.</p>
        <p>&quot;Manual and Loop&quot; allows you to manually set the video length
          with the duration text box and then will loop the video.</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>| **Speed** | Speed up the video speed. |
| :--- | :--- |


| **Maintain Aspect Ration** | If selected , then the video aspect ratio \(16:9 or 4:3\) will be used, else the effect will attempt to change the aspect ratio to better match the model dimensions. |
| :--- | :--- |


| **Use sequence audio file as video file and synchronize** | If using a video file as the sequence audio track, this options will use this file to display the video. |
| :--- | :--- |


| **Crop** | Trim the size of the video's resolution. |
| :--- | :--- |


| **Transparent Black** | Allow black pixels to be transparent. Slider adjust at what level "black" becomes transparent. |
| :--- | :--- |


{% hint style="danger" %}
If you move the image that you have used for the video effect to a different location or delete it, when you next run the sequencer, if the image is not found, an error message will not be displayed, but the effect will render a blank image. The only time this won’t happen is if only the drive letter has changed, and the rest of the path is the same.
{% endhint %}

{% hint style="warning" %}
If the Video Effect is appearing as a "Red" video, the video effect cannot find the video file.
{% endhint %}

