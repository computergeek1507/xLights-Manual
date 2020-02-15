# Piano

![Icon](../../.gitbook/assets/image%20%28657%29.png)

![Sequencer Grid](../../.gitbook/assets/image%20%28582%29.png)

![](../../.gitbook/assets/image%20%28321%29.png)

The Piano effect displays a piano keyboard effects where the keys modulate based on the beat and frequency of the sequence audio.  In addition to generating the effect using xLights inbuilt capability to process sound waves , you can also use an externally created Polyphonic Transcription notes file or an external midi file.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Option/Setting</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Notes Source</b>
      </td>
      <td style="text-align:left">
        <p>Indicates what the source for generating the Piano effects is.
          <br />
        </p>
        <p>Options are:</p>
        <p>Audacity Timing file, Midi file, xLights generated Polyphonic Transmission
          or Notes Source.
          <br />
        </p>
        <p>If Polyphonic transmission is selected, then a window will be displayed
          and there will be a pause whilst the timings are first generated.
          <br />
        </p>
        <p>If &#x2018;Audacity Timing file&#x2019; is selected, you will be prompted
          for the location of the Audacity file.
          <br />
        </p>
        <p>If &#x2018;Midi file&#x2019; is selected, you will be prompted for the
          location of the Midi file.
          <br />
        </p>
        <p>If Notes Source is selected, then a timing track source can be used (further
          described after the table). This is the preferred option.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Type</b>
      </td>
      <td style="text-align:left">Indicates how the piano keys should be displayed - &#x2018;True Piano&#x2019;
        or &#x2018;Bars&#x2019;.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Start Midi Channel</b>
      </td>
      <td style="text-align:left">The Start and End Midi channels defines the range that the Piano keys
        should emulate. The wider the range, the more keys are required. 64 corresponds
        to the &#x2018;Middle C&#x2019; key on the Piano.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>End Midi Channel</b>
      </td>
      <td style="text-align:left">See Start Midi Channels.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Show Sharps and Flats</b>
      </td>
      <td style="text-align:left">If selected , then the Sharp and Flat &#x2018;Black&#x2019; keys of the
        piano are shown and played.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Vertical Scale</b>
      </td>
      <td style="text-align:left">
        <p>Used to adjust the height of the effect vertically i.e. lengthen or shrink
          the effect.</p>
        <p>Can be adjusted via the Value Curves options.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Horizontal Offset</b>
      </td>
      <td style="text-align:left">Controls the position of the effect horizontally ie can be shifted left
        or right.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>File</b>
      </td>
      <td style="text-align:left">The name and location of the polyphonic transmission label file or Midi
        file if one of these have been selected as the source.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Track</b>
      </td>
      <td style="text-align:left">If a Midi file is selected , a list of Tracks that the file contains is
        displayed. You can select one of them or All (in which case the tracks
        are merged).</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Midi Start Time Adjust</b>
      </td>
      <td style="text-align:left">If a Midi file has been selected , this attribute can be used to adjust
        the synchronisation of the midi file to the song being sequenced in case
        they are slightly off from each other.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Midi Speed Adjust</b>
      </td>
      <td style="text-align:left">If a Midi file has been selected , this attribute can be used to adjust
        the tempo (increase or slow down). It is used to try to match tempos of
        the songs.</td>
    </tr>
  </tbody>
</table>Source = Timing Track

Set the source to timing track and select the Track from the list of Timing tracks you have generated in the sequence.

![](https://lh3.googleusercontent.com/1UJGiFxLvYDcANxRkSqT4ct1LmXs1Tl9EXiU2ZvNMYowTNbTDVDCytHDbJYlieZVwsLK544VHys6731hQ9R6eKi4_oZfbi-wNvGIiNf4bBZiGq2I9kjqYe4JHbQo75_xaOju2r55)

Then, expand the view so that you can see the labels of the timing track and change the labels to match the required keys.  The label can be the key letter or can be the MIDI value of the key.

You can also specify multiple values in one label and accordingly multiple keys will be depressed.

![](https://lh6.googleusercontent.com/F-W7L5yQtuDGkcDMk0jPYNFaUFHuQEOZD2zfXduedsrDKx9SzFo3YoB0o7ImJ8h-Uk8Y-FUDiqnxwKDvYbb3GWWTzaP0uIB5SAMhbU8vWwkkVcTwIEIAyKQffUAv9U6X1peGU5Ci)

You can use a value of C\# to depress the C\# key , C to depress the C key or multiple values such as C F A to depress three keys.

Multiple key formats are supported:

* 1-127: midi codes
* C4 or c\#4: note and octave
* C or C\#: notes \(assumed to be 4th octave\)

 Keys are separated by space, comma or colons.

