# Tools

## Tools

![](../../../.gitbook/assets/image%20%28606%29.png)

The Tools menu contains the Test , Convert, Generate Custom Models, View Logs, Package Problem Files, Export Models, Export Effects, FPP Connect, Package Sequence, and xSchedule  functions.

### Test

The Test Dialog enables you to test anything from a single channel, all channels for a model or all channels by sending different test patterns to your physical lights.

![](https://lh5.googleusercontent.com/0Dm4AzgxkGb-lfbRgygMuSwoOJ0K0UiRCaOJljoXv5qhFzxBO-nTPhZVS4Rm3QdmNTy8taq2gHSnbWRL8vGZbdlNBctKmISkDPfe5o3zRjA89QL0J4qOTBqUqaWi2MwiXY66R0Rh)

{% page-ref page="test.md" %}

### Convert

The Convert function is commonly used to convert a sequence file from one sequencer format to the format of another sequencer or to the format \(.fseq\) required to run via Falcon Player on a Raspberry Pi or BeagleBone Black controller.

![](https://lh3.googleusercontent.com/f2m_JsfnS2zBWjhM3gnV0WSCT0f2i2I9V-7xGS8npXF1XVvUB-nuT3A-hyi37N78KJ9AD-b2aIGVNcZv_0OlhBbYuoUvHfWzp_wWFuxvJ7sQrQWoGVx4WgkV1n8DEv7UmW3bf_4N)

{% page-ref page="convert.md" %}

{% hint style="warning" %}
This is not to be used to convert files into an xLights sequence – use the Data Layer or Import, Import Effects options to achieve that.
{% endhint %}

### Generate Custom Model

The Generate Custom Model function enables you to generate an xLights custom model using a picture or video of the physical item. You should have defined your controller and need to know which channel the model will start on and how many channels.

![](https://lh3.googleusercontent.com/8thtDKSP9l0Qm8lC2w93bXvT8gBE2aGk-899iKOqrjhHFMBhVwlNoxPEFXj9k6lAr5zQjOx_ZZkb6aM4kzicti_ksQRs9Uv5JANnMatbPppQLZqmiCbNiglqQmuqQV5x_R-00_fS)

{% page-ref page="generate-custom-model.md" %}

### Generate Lyrics From Data

The Generate Lyrics From Data allows xLights to generate Lyric Timing Tracks with Phonemes from channel data. This data can be a LOR LMS or LAS file, that has been imported as a data layer first. Select the start channel of the channel data and the offset for each mouth movement channel. xLights will then generate the Phonemes Track from this data.

![](../../../.gitbook/assets/image%20%28410%29.png)

### Generate 2D Path

This 2D Path Generate Tool allows you to create X and Y value curve "paths" that can then be used by effects like the shape effect. 

![](../../../.gitbook/assets/image%20%28727%29.png)

Click and Drag the endpoint Dots, to move them. Double Click to add a new Line Segment. The Browse button allows the user to load a image to trace if needed. The slider will adjust the image brightness. Load will allow you to edit previously generated files. The Generate Button will save the path to two value curves  files \(X & Y Direction\) to be loaded by an effect.

![ Value curve Files](../../../.gitbook/assets/image%20%28613%29.png)

### Prepare Audio

Prepare Audio allows xLights to load an audio "Cut List" file and edit an audio file to remove sections of a song or combine multiple songs. Reaper files\(.rpp\) and xAudio Files \(.xAudio\) Files. 

### Check Sequence

The Check Sequence option runs a series of verification routines against the currently loaded setup, layout and sequence.  This process will generate a text file containing information on the controller outputs, channel mappings and model information as well as identify any potential issues which could cause problems within xLights.  Selecting the option will open up a text file using the default text file editor on your computer.

![](https://lh3.googleusercontent.com/P31ipFUYMnP5Q32CAklY25M7nFZXsD-ugsO8FqJykqrn7gtN7-Sn73mFYEAUix74bn6e0Ot_tWsFBNhcdUERmBNzjQfZw5GjqTRIoCLMEKKU8pa5Ba6l7FhTsv6Q3ajYnSkt3Ktx)

{% hint style="warning" %}
ERRORS in a check sequence file indicate there is something wrong with your setup, layout, or sequence and the show will not run correctly.  Errors should be fixed before trying to run the sequence from your controllers.

WARNINGS are indications that something is not typical, but the show will still run.  Verifying that the warnings are intended, or correcting their cause is recommended before running the sequence from your controllers.
{% endhint %}

### Cleanup File Locations

Cleanup File Locations will move all the files currently used by xLights \(audio, videos, pictures, etc\) into the Show directory.  This is useful when backing up or packaging your sequence for sharing, so that all of the needed files and paths are retained.

### View Log

The View Log option, enables a user to view the information / debug log that xLights maintains, if required to troubleshoot any problems and provide information when posting questions. Selecting the option will open up a text file using the default text file editor on your computer. Scroll to the bottom to view the latest messages that have been written to the log.

![](https://lh6.googleusercontent.com/N21HiHaQcJFcMsz6Am_1JFiyyeBCxXVZU7hL4EFCOLwFg4Yppyfg2VhPw2ugpu3vDZn-QYYdN3gvXB1nOsdCl5xMp5XvMOtoLWX7_O7Niprw7UzUuOPYDGYPyABMxNF0Vqb3cPt4)

![](https://lh6.googleusercontent.com/lscnTcix3-SwMkjR-uFM7VHHMm6KNbCzv8dEY3C0XFvoydvjJ0mF_aR9KQB6L7eUM1-dtHrKlHLvYUvraGQXxdCl7IWXM94glzxyBj7PO7sNvAy4iazRTtRf5JLY3NLeVU_erdzy)

### Package Log Files

The Package Log Files option, provides functionality to package the required xLights XML and log files  into a ZIP file which can then be provided for analysis. It is similar in content to the ZIP file created when a system crash occurs.

![](https://lh5.googleusercontent.com/-Sc_QZp5wnF-aP1Gj351dCD76o1KsYhdAysm4tXK77DVzyb2GDmsy9faUdwBIAi1CHQKVnc8VBLTmfy60g63orHe7tvcKyoCm30Rd_AV7CDToz-4ckqi5kjBzw1LJzzpoXezctA4)

From the Tools menu, with the sequence that needs to be investigated open, select the Package Log  Files option.  The required files will be zipped into a file ‘xLightsProblem.zip’ and you will be prompted to save it in the show directory.

You can change either the ZIP file name and/or the location before saving the file.

![](https://lh5.googleusercontent.com/6BCqngjJSMXgHXu5sg_p0ujJO_Fdw1Zky3oyQXB4Po6b380rUTe354PzOQYHwCoOhmXE5E0dIO10hSoAaGZ-A097ziKj3Aj__UVa8rHCMFc4cMZWHjX0yMlNio33ikupvYlffK6i)

The zip file will contain the xLights network, rgbeffects, the sequence xml \(if open is open\) and a log file.  The zip file can then be provided to the xLights team for analysis.

### Export Models

The Export Models functionality creates a CSV file with the details of all your models. Click on the Export Models menu item. You will be prompted for a filename and location to create the file in. Specify the filename and click OK.

![](https://lh5.googleusercontent.com/ZTQb1VaEXFBzwYEkK0NC5z8RONzdQDSHpkIzqqGLbxySm8j8B4poKx1o4FI5B49UuOkgRVpPdD0VJZiuxtPVMXRY4WezP-MSEQflyHe00VVfefzZTcutNocriLG2BT0HW9Xxn2fc)

A CSV file will be created with a row for each model defined listing all the key attributes.  Spreadsheet programs such as Excel are used to view CSV files.

![](https://lh5.googleusercontent.com/Ng4CzpTHY-h6Y0K-bYhN1m43tYah9lQ-Bq8uEYyQMWgJjXm-gmi_3-s0pVPDhjRQiEU5OWgontRRuZtm-7_TmvM-p_mKDEYkpCqg0gZ_7yR20ToyIQ_JRc1WHhGQS5UDMidnjhlf)

### Export Effects

The Export Effects functionality creates a CSV file with the details of all the effects in the open sequence. Click on the Export Effects menu item. You will be prompted for a filename and location to create the file in. Specify the filename and click OK.

A CSV file will be created with a row for each effect defined listing all the key attributes.  In addition summary rows are created showing the number of times each sequence is used as well as the total duration of each effect.

![](https://lh5.googleusercontent.com/ZTQb1VaEXFBzwYEkK0NC5z8RONzdQDSHpkIzqqGLbxySm8j8B4poKx1o4FI5B49UuOkgRVpPdD0VJZiuxtPVMXRY4WezP-MSEQflyHe00VVfefzZTcutNocriLG2BT0HW9Xxn2fc)

### FPP Connect

![](../../../.gitbook/assets/image%20%28350%29.png)

FPP Connect is used to upload to a Falcon Pi Player that is playing the role as a show player the channel and model configurations and one or more sequences \(including associated audio\).

{% page-ref page="fpp-connect.md" %}

### User Lyric Dictionary

![](../../../.gitbook/assets/image%20%28374%29.png)

The User Lyric Dictionary Dialog allows the user to manually add word phonemes breakdowns to the user dictionary file in the current show folder. This list will be used in addition to the standard and extended library, to breakdown works when creating lyric tracks. Enter your new work into the first text box. The second text box will auto search the current word list and find similar words and display their phonemes. The second box supports multiple words separated by a space. Once you are happy with the phonemes breakdown you can add it to the library. 

![](../../../.gitbook/assets/image%20%28592%29.png)

### Download Sequences/Lyrics

The Download Sequences/Lyrics Dialog provides a list of free sequences available on the Google Drive. You can select a Sequence to download and xLights will open the download link in your default web browser. 

This Dialog also contains links to the Singing Faces Project Lyric tracks. You must be a member of the singing faces project to access these files.

![](../../../.gitbook/assets/image%20%28646%29.png)

### Batch Render

![](../../../.gitbook/assets/image%20%28730%29.png)

Batch Render allows the user to re-render multiple sequence files. This is useful if a Layout change was made and all the FSEQ files need to be updated. The "Filter" drop-down allows the user to select which folders to search for the sequence XML files in. 

* Recursive Search - No Backups
  * Search the show folders and sub-folder **not** including backup folders.
* Recursive Search
  * Search the show folder and sub-folder **including** backups folders.
* Only Show Directory
  * Search Only the root show folder.

If "Recursive Search" or "Recursive Search - No Backups" is selected the "Folder" drop-down allows the user to select a sub-folder to limit the search too.

Place a check-mark next to the sequence XML file name you plan to batch render. There is a right click menu to Select All or Select None.

![](../../../.gitbook/assets/image%20%2884%29.png)

Click OK to render all the Sequence XML file. 

{% hint style="warning" %}
If a Error is found during batch rendering, xLights will display a popup and will stop rendering. Monitor batch rendering to verify all the FSEQ files are created correctly.
{% endhint %}

### Package Sequence

This option will take the currently open sequence and packages it up neatly into a zip file with all the images, audio and other files necessary to open and re-render this sequence on another computer. If you plan on sharing a sequence with another person then this is the best way to ensure you grab everything the recipient will need to open and use your sequence.

### xSchedule

On windows and Linux this menu option will launch the xLights scheduler/player xSchedule.

### Purge Download Cache

To speed up loading, xLights caches\(saves\) the download items\(Vender Model List, Free Sequence List\) for up to 5 days. Purge Download Cache deletes the cached files and forces xLights to downloaded the newest version.  This is needed when there are updated to the files available for download, but xLights is not seeing the newest list.

### Purge Render Cache

The Render Cache is used to save rendered effects data to speed up render times. This option deletes the cache and forces xLights to re-render all the effects.

