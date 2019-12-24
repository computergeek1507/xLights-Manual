# Warp

![Icon](../../.gitbook/assets/image%20%28268%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28577%29.png)

![](../../.gitbook/assets/image%20%28134%29.png)

The Warp Effect is a canvas mode effect. By itself it does nothing. The warp effect distorts the pixels in the layers below it. The Canvas option in Layer Blending must be enabled for it to work.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Option/Settings</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Warp Type</b>
      </td>
      <td style="text-align:left">
        <p>Defines the type of Warp to use.</p>
        <p></p>
        <p>&quot;water drops&quot; Adds ripples simulation a stone falling in a lake.</p>
        <p></p>
        <p>&quot;dissolve&quot; pieces of the underlying effect disappear and reappear
          over time.</p>
        <p></p>
        <p>&quot;circle reveal&quot; underlying effect fades in/out with a circular
          pattern.</p>
        <p></p>
        <p>&quot;banded swirl&quot; mix the underlying effect, like mixing colors
          in water.</p>
        <p></p>
        <p>&quot;ripple&quot; bounce the underlying effect up and down like it was
          laying on a trampoline.</p>
        <p></p>
        <p>&quot;single water drop&quot; Adds ripple simulation a single water drop.</p>
        <p></p>
        <p>&quot;circular swirl&quot; mix the underlying effect, with a circular
          pattern.</p>
        <p></p>
        <p>&quot;drop&quot; underlying effect &apos;melts&apos; downward.</p>
        <p></p>
        <p>&quot;wavy&quot; Move the underlying effect to simulate a flag waving
          in the wind.</p>
        <p></p>
        <p>&quot;sample on&quot; Sample one pixel from the underlying effect. The
          X,Y slider control the X,Y location of the pixel to sample.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Treatment</b>
      </td>
      <td style="text-align:left">
        <p>&quot;Constant&quot; repeat the effect over and over.</p>
        <p></p>
        <p>&quot;In&quot; Preform the effect once with the &quot;In&quot; direction.</p>
        <p></p>
        <p>&quot;Out&quot; Preform the effect once with the &quot;Out&quot; direction.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>X</b>
      </td>
      <td style="text-align:left">X screen location of the effect.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Y</b>
      </td>
      <td style="text-align:left">Y screen location of the effect.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cycle Count</b>
      </td>
      <td style="text-align:left">If &quot;Constant&quot; treatment is enabled, this specified the number
        of times the effect repeats.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Speed</b>
      </td>
      <td style="text-align:left">Adjust the speed of the effect</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Frequency</b>
      </td>
      <td style="text-align:left">Adjusts the rate the &quot;ripple&quot; and &quot;banded swirl&quot; manipulate
        the effect.</td>
    </tr>
  </tbody>
</table>{% hint style="danger" %}
This Effect using a lot of CPU resources. If it is placed on large model groups, like whole house model groups, it **WILL** increase render times significantly.
{% endhint %}

