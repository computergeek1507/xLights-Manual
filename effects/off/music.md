# Music

![Icon](../../.gitbook/assets/image%20%28353%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28562%29.png)

![](../../.gitbook/assets/image%20%28737%29.png)

The Music effect analyses and displays a representation of the frequency breakdown of the song from the waveform.  Select at least two colors.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Option/Settings</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Bars</b>
      </td>
      <td style="text-align:left">Controls the number of bars that are displayed for the effect. The bars
        displayed is also influenced by the range of notes selected.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Type</b>
      </td>
      <td style="text-align:left">
        <p>Separate - Color bars starts in the middle and separates out.</p>
        <p>Morph - starts at the bottom and goes to the top. (Use layer settings
          to change/rotate direction).</p>
        <p>Bounce - Similar to Morph , but bounces after each completion.</p>
        <p>Collide - Color bars starts at the outside and move inwards.</p>
        <p>On - The bar comes on and fades away.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Start, End Note</b>
      </td>
      <td style="text-align:left">Controls (narrows) the range of notes (MIDI values) that are used for
        the effect i.e notes outside this range will be filtered out. Value 60
        corresponds to &#x2018;Middle C&#x2019; .</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Sensitivity</b>
      </td>
      <td style="text-align:left">Controls the threshold level of the music at which the effect gets triggered.
        The effect will last as long as the intensity is above the threshold. Increasing
        the sensitivity raises the threshold and therefore reduces the effects.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Offset</b>
      </td>
      <td style="text-align:left">
        <p>Enables the effect to be moved horizontally to the left or right. Useful
          if you wish to layer another effect offset in the other direction.</p>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Scale Bars</b>
      </td>
      <td style="text-align:left">If selected, will cause the bars to be spread out (i.e scaled across the
        whole effect spectrum).</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Note Scaling</b>
      </td>
      <td style="text-align:left">
        <p>If selected , will increase activity of All/Individual notes in quiet
          areas of the song. Using scaling makes effects trigger easier.
          <br />
        </p>
        <p>Options:</p>
        <ul>
          <li>None: Notes aren&#x2019;t scaled.</li>
          <li>Individual notes: Each notes is scaled such that every note will reach
            100% at some time during the duration of the effect.</li>
          <li>All notes: Notes are scaled such that one note will reach 100% at some
            time during the duration of the effect.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Color</b>
      </td>
      <td style="text-align:left">
        <p>Changes the way that the colors are rendered . Options are Distinct ,
          Blend or Cycle.</p>
        <p>For the Cycle option, the first time the note is triggered, the first
          color of the palette will be selected, the next time the second color etc
          as the colors are cycled through.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Fade</b>
      </td>
      <td style="text-align:left">Controls whether the effect fades over it duration.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Logarithmic X Aris</b>
      </td>
      <td style="text-align:left">Change the x-axis scale to logarithmic. This will better even out the
        auto waveform on the low frequency end.</td>
    </tr>
  </tbody>
</table>