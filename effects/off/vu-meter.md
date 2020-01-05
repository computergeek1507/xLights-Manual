# VU Meter

## VU Meter

![Icon](../../.gitbook/assets/image%20%28613%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28595%29.png)

![](../../.gitbook/assets/image%20%28414%29.png)

The VU Meter effect displays a volume meter type of effects that responds to the sound level of an audio track. Each bar represents a note on the scale and the height of each bar represents the intensity.

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
      <td style="text-align:left">Controls the number of bars to be used for the effect.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Type</b>
      </td>
      <td style="text-align:left">
        <p>Controls the type of Waveform that is displayed. Options are:
          <br />
        </p>
        <p>&quot;Spectrogram&quot; visual representation of the audios frequencies.
          Bends color pallet values together based on audio level.</p>
        <p></p>
        <p>&quot;Spectrogram Peak&quot; same a &quot;Spectrogram&quot; but used last
          color pallet option to draw a peak line.</p>
        <p></p>
        <p>&quot;Spectrogram Line&quot; line that represents the audios frequencies
          levels.</p>
        <p></p>
        <p>&quot;Spectrogram Circle Line&quot; uses circles to represents the audios
          frequencies levels.</p>
        <p></p>
        <p>&quot;Volume Bars&quot; draws bars based on audio levels.</p>
        <p></p>
        <p>&quot;Waveform&quot; Displays the audio waveform.</p>
        <p></p>
        <p>&quot;Frame Waveform&quot; Displays the audio waveform only using the
          current frame of audio.</p>
        <p></p>
        <p>&quot;On&quot; will shows brightness equivalent to the volume of music</p>
        <p></p>
        <p>&quot;Color On&quot; will change color (from the palette) as the intensity
          of the music increases.</p>
        <p></p>
        <p>&quot;Intensity Wave&quot; Scrolls vertical bars across with brightness
          based on the music intensity.</p>
        <p></p>
        <p>&quot;Pulse&quot; Fade In and Out a Color based on the timing marks.</p>
        <p></p>
        <p>&quot;Level Bar&quot; Scrolls a vertical bar across with movement based
          on audio level.</p>
        <p></p>
        <p>&quot;Level Color&quot; Cycles panel colors based on the audio level.</p>
        <p></p>
        <p>&quot;Level Pulse&quot; pulses when the audio gets above a certain level.</p>
        <p></p>
        <p>&quot;Level Jump&quot; The effect with &quot;jump&quot; to the audio level
          when the sensitivity level is crossed by the audio level.</p>
        <p></p>
        <p>&quot;Level Jump 100&quot; The effect with &quot;jump&quot; to 100 percent
          when the sensitivity level is crossed by the audio level.</p>
        <p></p>
        <p>&quot;Level Pulse Color&quot; pulses when the audio gets above a certain
          level and changes colors with each pulse.</p>
        <p></p>
        <p>&quot;Level Shape&quot; display the selected shape with a size that adjusts
          based on the audio level.</p>
        <p></p>
        <p>&quot;Timing Event Bar&quot; Scrolls a vertical bar across with each timing
          mark.</p>
        <p></p>
        <p>&quot;Timing Event Bars&quot; Display multiple bars that shift with each
          timing mark.</p>
        <p></p>
        <p>&quot;Timing Event Spike&quot; Sweeps a vertical bar across with each
          timing mark. Single Color</p>
        <p></p>
        <p>&quot;Timing Event Sweep&quot; Sweeps a vertical bar across with each
          timing mark. Blends All the color pallet options.</p>
        <p></p>
        <p>&quot;Timing Event Sweep 2&quot; Sweeps a vertical bar across with each
          timing mark. Sliced bar based by the color pallet options.</p>
        <p></p>
        <p>&quot;Timing Event Timed Sweep&quot; Sweeps a vertical bar across with
          each timing mark. Speed is based on timing mark spacing. Blends All the
          color pallet options.</p>
        <p></p>
        <p>&quot;Timing Event Timed Sweep 2&quot; Sweeps a vertical bar across with
          each timing mark. Speed is based on timing mark spacing. Sliced bar based
          by the color pallet options.</p>
        <p></p>
        <p>&quot;Timing Event Alternate Timed Sweep&quot; Sweeps a vertical bar across
          with each timing mark. Will bounce back and forth. The full bar with disappear
          off the buffer before the &quot;bounce&quot; occurs. Blends Sliced bar
          based by the color pallet options.</p>
        <p></p>
        <p>&quot;Timing Event Alternate Timed Sweep 2&quot; Sweeps a vertical bar
          across with each timing mark. Will bounce back and forth. The bar will
          &quot;bounce&quot; when it touched edge of the buffer. Blends Sliced bar
          based by the color pallet options.</p>
        <p></p>
        <p>&quot;Timing Event Color&quot; will change color based (from the palette)
          triggered on the timing of the Timing Track selected.</p>
        <p></p>
        <p>&quot;Timing Event Jump&quot; will cause a &quot;jump&quot; at each event
          (i.e. bars/beats) of the timing track selected based on the audio level.</p>
        <p></p>
        <p>&quot;Timing Event Jump 100&quot; will cause a Spike at each event (i.e.
          bars/beats) of the timing track selected but will fill the full vertical
          resolution.</p>
        <p></p>
        <p>&quot;Timing Event Pulse&quot; pulses based on the timing marks using
          a single color.</p>
        <p></p>
        <p>&quot;Timing Event Pulse Color&quot; pulses based on the timing marks
          and cycling through the color on each pause.</p>
        <p></p>
        <p>&quot;Note On&quot; will shows brightness based on the note range intensity.</p>
        <p></p>
        <p>&quot;Note Level Pulse&quot; will turn on a color (i.e pulse) when the
          note range crosses the sensitivity level and then quickly fade out.</p>
        <p></p>
        <p>&quot;Node Level Jump&quot; The effect with &quot;jump&quot; to the audio
          level when the sensitivity level is crossed by the audio level.</p>
        <p></p>
        <p>&quot;Node Level Jump 100&quot; The effect with &quot;jump&quot; to 100
          when the sensitivity level is crossed by the audio level.</p>
        <p></p>
        <p>&quot;Note Level Bar&quot; Sweeps a vertical bar across when the note
          range crosses the sensitivity.</p>
        <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Timing Track</b>
      </td>
      <td style="text-align:left">Defines the timing track from the sequence against which the effect will
        be generated. This is only available for some types of effects as in other
        cases the effect is generated off the audio level or audio spectrum.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Sensitivity</b>
      </td>
      <td style="text-align:left">Controls the threshold level of the music at which the effect gets triggered.
        The effect will last as long as the intensity is above the threshold.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Gain</b>
      </td>
      <td style="text-align:left">Gain for effects movement level.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shape</b>
      </td>
      <td style="text-align:left">
        <p>Enabled when the Type attribute is &#x2018;Level Shape&#x2019;. Options
          are:</p>
        <p>Circle, Square, Diamond, Star, Tree, Crucifix, Present, Candy Cane, Snowflake,
          Heart. Filled or Unfilled.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Show Down Falls</b>
      </td>
      <td style="text-align:left">Averages audio levels to smooth out shape size and spectrogram height.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Start Note, End Note</b>
      </td>
      <td style="text-align:left">Controls (narrows) the range of notes (MIDI values) that are used for
        the effect i.e notes outside this range will be filtered out. Useful to
        filter out the bottom notes or the top notes in different songs. Value
        60 corresponds to &#x2018;Middle C&#x2019; .</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Logarithmic X axis</b>
      </td>
      <td style="text-align:left">Use Logarithmic X axis for bar spacing. This will better even out the
        auto waveform on the low frequency end.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Horizontal Offset</b>
      </td>
      <td style="text-align:left">This attribute adjusts the center of the effect horizontally.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Vertical Offset</b>
      </td>
      <td style="text-align:left">
        <p>This attribute adjusts the center of the effect vertically.</p>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
  </tbody>
</table>