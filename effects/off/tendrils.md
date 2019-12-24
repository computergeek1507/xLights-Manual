# Tendrils

## Tendril

![Icon](../../.gitbook/assets/image%20%2882%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28163%29.png)

![](../../.gitbook/assets/image%20%2845%29.png)

The Tendrils effect provides an effect which looks like a twisting threadlike structure.You can think of tendrils as the pattern you would see if you took a piece of string, held it just above a flat surface and moved it around. As you do so the string would move leaving a trail which did not exactly match the movements but was a result of it. The parameters of the tendril effect let you control the movement of the string and how the string behaves.

Only one color can be used for the effect.

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
        <p>This describes how the end of the string is being moved. Available movements
          include:</p>
        <ul>
          <li>Random - The string on each frame is randomly moved somewhere else on
            the model. This creates dramatic but random movements.</li>
          <li>Square - The string is moved around the edge of the model from corner
            to corner anti-clockwise.</li>
          <li>Circle - The string is moved around the centre of the model in a circle
            clockwise.</li>
          <li>Horizontal Zig Zag - the string is dragged left to right and back again
            across the model slowly moving up and down the model. With the right settings
            this can almost look like a spiral tree.</li>
          <li>Horizontal Zig Zag Return - As per Horizontal Zig Zag , but the string
            drops down straight to the starting point at the end of the zig zag.</li>
          <li>Vertical Zig Zag Return - As per Vertical Zig Zag , but the string returns
            straight to the starting point at the end of the zig zag.</li>
          <li>Music Line - The string is moved left and right across the model with
            the vertical movement determined by the intensity of the associated music
            in that frame.</li>
          <li>Music Circle - The string is moved in a circle clockwise with the distance
            the string is from the center of the circle determined by the intensity
            of the associated music in that frame.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Tune Movement</b>
      </td>
      <td style="text-align:left">
        <p>The tune movement slider adjusts the current movement. This works differently
          for each movement.</p>
        <ul>
          <li>Random - Tunes how far each random movement is. Smaller means smaller
            movements.</li>
          <li>Square - Tunes how many steps the string takes moving from one corner
            to the next. Larger numbers make the movement slower</li>
          <li>Circle - Tunes how many degrees the string takes moving around the circle.
            Larger numbers make the movement faster.</li>
          <li>Horizontal Zig zag - Tunes the number of zig zags on each traversal of
            the model. Large numbers reduce the number of traversals.</li>
          <li>Vertical Zig zag - Tunes the number of zig zags on each traversal of the
            model. Large numbers reduce the number of traversals.</li>
          <li>Music Line - Tunes the speed the line travels left and right across the
            model. Large numbers speed up the line.</li>
          <li>Music Circle - Tunes the speed the line travels around the circle. Large
            numbers speed up the line.</li>
          <li>Speed - This allows you to lower the frame rate. 10 is full speed. Anything
            lower will make the movement slower and jerkier.</li>
        </ul>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Thickness</b>
      </td>
      <td style="text-align:left">
        <p>This is how thick the string is. By default it is just 1 pixel wide.</p>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Friction</b>
      </td>
      <td style="text-align:left">Friction is how much the surface resists the string moving. When set low
        friction is high and the string won&#x2019;t move much. When set high the
        string will wildly flap about.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Dampening</b>
      </td>
      <td style="text-align:left">Controls how quickly the string will try to resume being in line with
        the tail point. When set low it will come back quickly. When set high it
        can take a long time to align.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Tension</b>
      </td>
      <td style="text-align:left">This behaves much like dampening. Set low and the tail of the string will
        tend to stay still and only the moving end will move much.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Trails</b>
      </td>
      <td style="text-align:left">The effect can draw multiple lines (not just the one). On low resolution
        displays or when thickness is set high it won&#x2019;t be seen. On higher
        resolution displays, if you set this to higher numbers, you will see the
        tendril fray into multiple related lines like a partially unravelled rope.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Length</b>
      </td>
      <td style="text-align:left">This is how long the string is. By default it is 60 segments long.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Speed</b>
      </td>
      <td style="text-align:left">This enables you to lower the frame rate. 10 is full speed. Anything lower
        may make the movement slower and jerkier</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Horizontal, Vertical Offset</b>
      </td>
      <td style="text-align:left">
        <p>Enables adjustment to the starting position of the effect horizontally
          and/or vertically.</p>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Manual X, Y</b>
      </td>
      <td style="text-align:left">
        <p>Controls the X and Y positions of the effect.</p>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
  </tbody>
</table>