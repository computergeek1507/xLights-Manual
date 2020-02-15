# Text

## Text

![Icon](../../.gitbook/assets/image%20%28187%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28148%29.png)

![](../../.gitbook/assets/image%20%28215%29.png)

The Text effect enables up to 20 lines of text, all individually controlled to be displayed. The content of the text can be static, but can also include countdown timers.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Option/Settings</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Text</b>
      </td>
      <td style="text-align:left">Contains the text that is to be displayed for the line.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Font</b>
      </td>
      <td style="text-align:left">Defines the font that is to be used for the text. Click on the attribute
        to open up a window where the type of font, style, size, color and other
        related attributes can be defined.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>XL Font</b>
      </td>
      <td style="text-align:left">Use an OS defined font or Select one of the xLights defined fonts. The
        xLights defined fonts are intended to match LOR SuperStar and may look
        better on models with lower pixel density.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Movement / C</b>
      </td>
      <td style="text-align:left">
        <p>Defines the direction of the movement of the line of text. One of several
          options are possible such as Left, Right, Down, None, etc.</p>
        <p>If the box next to the Movement setting i.e. &#x2018;C&#x2019; is checked,
          then the text will reach the center and stop.</p>
        <p></p>
        <p>When the Vector option is selected, the Start Position and End Position
          tabs at the bottom are used to adjust the motion. 0,0 is the middle position.
          It defaults to offsetting with the values being percentages of the model
          size but if you check the Offsets in Pixels box it becomes number of pixels.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Speed</b>
      </td>
      <td style="text-align:left">Controls the speed at which the line of text moves.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Effect</b>
      </td>
      <td style="text-align:left">Controls the layout of the line of text. The default is &#x2018;Normal&#x2019;,
        however other options to rotate the text at different angles are possible.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Count down</b>
      </td>
      <td style="text-align:left">
        <p>Defines whether the line of text is to be used as a Countdown Timer. The
          default value is &#x2018;None&#x2019; indicating that it is not a Countdown
          Timer effect.</p>
        <p></p>
        <p>For a count down effect, the following options are possible and count
          down will be based from the time the effect is rendered or finally saved
          and not from when it is executed in the sequence. The concept of the count
          down timer stems from New Year&#x2019;s Eve countdown displays. If one
          knows exactly when the countdown will start, then setting this to an appropriate
          date/time is a non-issue.
          <br />
        </p>
        <p>The date/time must conform the the RFC822 standard format.</p>
        <p>Properly formatted examples are:
          <br />Fri, 25 Dec 2015 00:00:00 +0100</p>
        <p>Fri, 25 Dec 2015 00:00:00 EST</p>
        <p>Fri, 25 Dec 2015 00:00:00 MST</p>
        <p>Fri, 25 Dec 2015 00:00:00 -0800</p>
        <p>&lt;b&gt;&lt;/b&gt;</p>
        <p>These must be specified in the Text field without any quotes.
          <br />
          <br />seconds</p>
        <p>100</p>
        <p>Will execute a 100 second countdown
          <br />
        </p>
        <p>In the following examples &#x2018;+0100&#x2019; refers to your time +GMT
          hours. Change accordingly. Or you can use GMT, EST etc.</p>
        <p></p>
        <p>to date &#x2018;d h m s&#x2019;</p>
        <p>Fri, 25 Dec 2015 00:00:00 +0100</p>
        <p>Will display 33d 3h 38m 14</p>
        <p></p>
        <p>to date &#x2018;h:m:s&#x2019;</p>
        <p>Fri, 25 Dec 2015 00:00:00 +0100</p>
        <p>Will display 3h 38m 14 - the time is calculated to the next day in hours,
          mins, secs</p>
        <p></p>
        <p>to date &#x2018;m&#x2019; or &#x2018;s&#x2019;</p>
        <p>Fri, 25 Dec 2015 00:00:00 +0100</p>
        <p>Will display 217m - the time is calculated to the next day in minutes</p>
        <p></p>
        <p>to date &#x2018;s&#x2019;</p>
        <p>Fri, 25 Dec 2015 00:00:00 +0100</p>
        <p>Will display 13011 - the time is calculated to the next day in seconds</p>
        <p></p>
        <p>!to date !%tofmt</p>
        <p>/Fri, 25 Dec 2015 00:00:00 +0100/ %D</p>
        <p>Will display 133
          <br />
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Position</b>
      </td>
      <td style="text-align:left">
        <p>This setting is used to adjust the initial position of the text. Either
          the vertical (Y) or the horizontal (X) position of the text is adjusted,
          depending on the value of the &#x2018;Movement&#x2019; setting. For a value
          of &#x2018;None&#x2019; or a horizontal movement such as Left / Right,
          adjusting the setting will move the initial position of the text vertically.
          <br
          />
        </p>
        <p>Only the first line of text can be controlled vertically and horizontally.
          The other lines have a horizontal control only.
          <br />
        </p>
        <p>You can however use multiple Layers each with one or more text lines if
          required.</p>
      </td>
    </tr>
  </tbody>
</table>{% hint style="success" %}
In order to stop the text after one cycle, use the "Vector" Movement option and define your vector motion.  It will complete that motion in the duration of the effect. This option can also be used to stop text at a particular point on a matrix.
{% endhint %}

