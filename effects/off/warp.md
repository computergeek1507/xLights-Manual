# Warp

![Icon](../../.gitbook/assets/image%20%28337%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28680%29.png)

![](../../.gitbook/assets/image%20%28168%29.png)

The Warp Effect is a canvas mode effect. By itself it does nothing. The warp effect distorts the pixels in the layers below it. The Canvas option in Layer Blending must be enabled for it to work.

| Option/Settings | Description |
| :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Warp Type</b>
      </th>
      <th style="text-align:left">
        <p>Defines the type of Warp to use.</p>
        <p>&quot;water drops&quot; Adds ripples simulation a stone falling in a lake.</p>
        <p>&quot;dissolve&quot; pieces of the underlying effect disappear and reappear
          over time.</p>
        <p>&quot;circle reveal&quot; underlying effect fades in/out with a circular
          pattern.</p>
        <p>&quot;banded swirl&quot; mix the underlying effect, like mixing colors
          in water.</p>
        <p>&quot;ripple&quot; bounce the underlying effect up and down like it was
          laying on a trampoline.</p>
        <p>&quot;single water drop&quot; Adds ripple simulation a single water drop.</p>
        <p>&quot;circular swirl&quot; mix the underlying effect, with a circular
          pattern.</p>
        <p>&quot;drop&quot; underlying effect &apos;melts&apos; downward.</p>
        <p>&quot;wavy&quot; Move the underlying effect to simulate a flag waving
          in the wind.</p>
        <p>&quot;sample on&quot; Sample one pixel from the underlying effect. The
          X,Y slider control the X,Y location of the pixel to sample.</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table><table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Treatment</b>
      </th>
      <th style="text-align:left">
        <p>&quot;Constant&quot; repeat the effect over and over.</p>
        <p>&quot;In&quot; Preform the effect once with the &quot;In&quot; direction.</p>
        <p>&quot;Out&quot; Preform the effect once with the &quot;Out&quot; direction.</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>| **X** | X screen location of the effect. |
| :--- | :--- |


| **Y** | Y screen location of the effect. |
| :--- | :--- |


| **Cycle Count** | If "Constant" treatment is enabled, this specified the number of times the effect repeats. |
| :--- | :--- |


| **Speed** | Adjust the speed of the effect |
| :--- | :--- |


| **Frequency** | Adjusts the rate the "ripple" and "banded swirl" manipulate the effect. |
| :--- | :--- |


{% hint style="danger" %}
This Effect using a lot of CPU resources. If it is placed on large model groups, like whole house model groups, it **WILL** increase render times significantly.
{% endhint %}

