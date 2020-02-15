# Bars

![Icon](../../.gitbook/assets/image%20%28157%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28692%29.png)

![](../../.gitbook/assets/image%20%28549%29.png)

The Bars effect creates straight edged multiple color bars that move across a model.  The edges may be hard, highlighted or 3D \(soft\).

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Options/Setting</b>
      </th>
      <th style="text-align:left"><b>Description</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Palette Rep</b>
      </td>
      <td style="text-align:left">
        <p>
          <br />Number of times the color palette repeats on a model. All the colors selected
          will repeat as many times as this value is defined.</p>
        <p>Therefore , if 2 colors are selected and this value is 3, each of the
          2 colors will come on 3 times , resulting in 6 changes of colors.
          <br />
        </p>
        <p>This whole setting is multiplied by the Cycles value.</p>
        <p></p>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cycles</b>
      </td>
      <td style="text-align:left">
        <p>Number of cycles for the duration.
          <br />
        </p>
        <p>Therefore</p>
        <ul>
          <li>If set to 1, then the colors selected and palette rep combination will
            execute once.</li>
          <li>If set to 2 and there are 3 colors and the palette rep is set to 4 , then
            there will be 24 changes of color (2 cycles * (3 colors * 4 reps) ) in
            the selected duration.</li>
        </ul>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Center Point</b>
      </td>
      <td style="text-align:left">Enables you to control where the centre point is for expand and compress
        (both vertical and horizontal).</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Direction UP/DOWN</b>
      </td>
      <td style="text-align:left">Bars move UP or DOWN a model.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Direction Expand</b>
      </td>
      <td style="text-align:left">Bars start at the center and move outward towards the top and bottom.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Direction Compress</b>
      </td>
      <td style="text-align:left">Bars start at the top and bottom edges of a model and move to the center.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Direction Left/Right</b>
      </td>
      <td style="text-align:left">Bars start at the left/right edges of the model and move to the other
        side.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Direction H Expand</b>
      </td>
      <td style="text-align:left">Bars start at the horizontal middle of the model and expand towards the
        left and right edges.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Direction H Compress</b>
      </td>
      <td style="text-align:left">Bars start at the left/right edges of the model and move in towards the
        horizontal center of the model.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Direction Alternate</b>
      </td>
      <td style="text-align:left">Bars are not animated like the other direction options. The colors for
        each bar change to the next color selected in the palette.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Highlight</b>
      </td>
      <td style="text-align:left">A single row of white is set at the leading edge of each color.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>3-D</b>
      </td>
      <td style="text-align:left">The trailing edge of each color fades to black.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Gradient</b>
      </td>
      <td style="text-align:left">When selected, causes the different colors to merge into each other as
        a gradient rather than as a sharp change.</td>
    </tr>
  </tbody>
</table>{% hint style="success" %}
Layering a On effect with a start intensity of 0% and ending of 100% will result in a ramp up, as opposed to an On effect with hard edges.  Be sure to set the blending option of the On effect to “layer 1 is mask”. Make sure the cycle count is set to 1, and you have a color selected \(doesn't matter which color since it's a mask\).
{% endhint %}

