---
layout: default
title: Record Player
parent: Supported Formats and Equipment
grand_parent: Reformatting and Digitizing Materials
permalink: docs/Reformatting-And-Digitizing-Materials/supported-formats-and-equipment/record-player/
nav_order: 7
---

# Record Player
{: .fs-6 .fw-300 }

## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}

__Hardware__: [Technic Quartz SL-1200M3D](https://elizajames.github.io/digital-preservation-documentation/assets/files/technic.pdf), Roland Octa-Capture

__Software__: Audacity

## Identification and Introduction

Vinyl records have been in use since the 1940s. The most common sizes are: 7-inch, 10-inch, and 12-inch. Audio is encoded as physical soundwaves within the grooves on the disc. Damage to these grooves results in loss of audio. Both records and playback equipment are still being manufactured today making the format low-risk from a technological obsolescence perspective. However, all grooved disc media is susceptible to warpage, breakage, groove wear, and surface contamination. Surface contamination includes dirt, dust, mold, and other foreign materials, all of which can abrade or damage the grooves and diminish playback sound quality.  To learn more about vinyl records, see the University of Illinois at Urbana-Champaign's [documentation on the format](https://psap.library.illinois.edu/collection-id-guide/phonodisc#vinyldisc). 

The Digitization Lab can only handle 33 1/3 and 45 RPM speed records.

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_1_Image_0001.jpg" alt="Vinyl record">

## Digitization Procedures

### Inspect Item for Issues

- Be sure to handle the item by the edges. Do not touch the surface of the item directly. 
- If the surface appears to have dust or other debris on it, use the small brush hanging behind the desk to remove them. This ensures best quality playback. Brush in line with the grooves, not across them and against the grain. 

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_1_Image_0002.jpg" alt="Cleaning brush">

### Physical Setup

- Plug the red and white tipped cords for the cassette player, found hanging on the cubicle wall and labeled with __Cassette Player__, into the Roland sound interface (see image below). 

![Plugged in cables for OctaCapture](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingCassetteTapes-271122-0153-14_Page_2_Image_0001.jpg)

- Determine the appropriate rotations per minute (RPM) for your disc. This should be on the label, listed as RPM or Speed, plus the relevant number. If you can't determine the RPM, simply listen to the audio before recording it. If it sounds too slow or too fast, try the 45 RPM or 33 1/3 RPM respectively. 
- Lift the plastic dust cover off the record player and set aside.
- If your record has a large hole in the middle, grab the adapter in the upper left of the record player and place it over the spindle in the center of the record player. 

![Spindle on record player in storage compartment](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_2_Image_0002.jpg)

![Spindle on record player in place](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_2_Image_0003.jpg)

- Verify that the Roland sound interface and record player are plugged in to the surge protector below the desk. The cords are labeled as __Roland sound interface__ and __record player__ respectively. Turn on the devices by pressing and briefly holding the power button on the upper right of the Roland sound interface. Turn on the record player by moving the top of the power dial clockwise toward "On." The dial does not twist–only the black, circular part on top rotates. You'll know it's on when the side of the dial turns red.

![Record player on button](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_2_Image_0004.jpg)

- __33 1/3__ RPM should be selected automatically. If you have a 45 RPM record, press the __45__ button in the lower left area of the record player.

![Record player RPM buttons](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_3_Image_0001.jpg)

- Place the disc on the center of the record player.

### Selecting the Settings

- The settings chosen for digitization are based on whether digitization will be conducted at preservation or access quality. Preservation quality files are chosen when conducting digitization of materials for long-term retention and preservation and should be chosen when working with unique archival materials. The settings can be found under “33.33 and 45 RPM Records” in the [Digitization Standards Document](https://elizajames.github.io/digital-preservation-documentation/docs/Appendices/appendix2/#digitization-standards-document) and summarized here:  


|                     | __Preservation Settings__                | __Access Settings__                      |
|---------------------|--------------------------------------|--------------------------------------|
| __File Type__           | .WAV                                 | .MP3                                 |
| __Encoding__            | LPCM (Linear Pulse Code Modulation)  | LPCM (Linear Pulse Code Modulation)  |
| __Sampling Frequency__  | 96 kHz                               | 48 kHz                               |
| __Bit Depth/Rate__      | 24-bit                               | 16-bit                               |
| __Audio Channel__       | Stereo                               | Stereo                               |

- With the settings you have identified in mind, open __Audacity__ by clicking the shortcut on the desktop. Select the button for __Edit__ on the toolbar, then select __Preferences__. Click __Quality__ on the left toolbar of the __Preferences__ settings box (see below) that appears. Use the dropdowns for __Default Sample Rate__ (aka Sampling Frequency) and __Default Sample Format__ (aka Bit Depth/Rate) to select the relevant settings for your project.  

![Preferences Quality screen](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingCassetteTapes-271122-0153-14_Page_4_Image_0001.jpg)

- On the main Audacity screen, verify that you see “OCTA-CAPTURE” next to the microphone icon (boxed in red below) and “2 (Stereo) Recording Channel” next to that to make sure Audacity is connected to the Roland sound interface. If you don’t see it, verify that both the cassette player and Roland are on and exit out of and restart Audacity. You can also verify the sampling frequency in the lower left corner (boxed in red below). 

![Main Audacity screen](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingCassetteTapes-271122-0153-14_Page_4_Image_0002.jpg)

### Capture and Save Your Audio

-  If you need to determine a rough approximation of how much audio a record can hold, consult the table below. It's recommended that you minimize pausing while the record is playing and simply play the record through when digitizing to minimize the need for any audio editing.  

| __Size__    | __RPM__    | __Runtime per Side__ |
|---------|--------|------------------|
|  7-inch | 33 RPM |     7 minutes    |
|  7-inch | 45 RPM |     5 minutes    |
| 10-inch | 33 RPM |    15 minutes    |
| 10-inch | 45 RPM |    12 minutes    |
| 12-inch | 33 RPM |    22 minutes    |
| 12-inch | 45 RPM |    15 minutes    |

- To listen to the audio while it’s playing, plug the headphones in to the Roland sound interface (seen boxed in red below).

![Headphones image](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingCassetteTapes-271122-0153-14_Page_5_Image_0001.jpg)

- Press __Start/Stop__ to start rotating the record.

![Start/stop on turntable](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_5_Image_0002.jpg)

- Raise the tone arm off of its base using the black cue lever. Once the tone arm is in the up position, gently slide the tone arm over to a point just on outside margin of the record (outside where the tight grooves start).

*Raising the cue lever*

![Raising the cue lever](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_5_Image_0003.jpg)

*Placement of tone arm*

![Tone arm placement](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_6_Image_0001.jpg)

- Click the red __Record__ button at the top of the screen. 

![Record button in Audacity](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_6_Image_0002.jpg)

- Push down the black cue lever. This will release the tone arm to be gently lowered onto the record. Gently place the dust cover on top of the record player. It may take a moment for audio to begin playing.

![Pressing cue lever](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_6_Image_0003.jpg)

- In Audacity, you should see green bars moving across the numbers at the top, depicted below, as your record is playing. This means audio is being “heard” by Audacity. 

![Audio levels in Audacity](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingVinylRecords-271122-0154-22_Page_7_Image_0001.jpg)

- If you need to verify audio is being heard, simply raise the tone tone arm using the cue lever and play back the recording using the __Play__ button. If you hear the recording, you are fine to proceed by starting the record from the beginning.  
- To adjust recording volume as needed, move the slider next to the microphone icon in the upper right corner of the screen toward the minus sign (softer) or the plus sign (louder), as shown below. If the volume is already at the maximum and is still too soft, this can be managed once digitization is complete by following the [Audacity Increase Volume Tutorial](https://www.youtube.com/watch?v=BKHFHG0frEA).

![Audio bar Audacity](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingCassetteTapes-271122-0153-14_Page_5_Image_0005.jpg)

- You should see activity in the window like that in the screenshot below. The size of the upper and lower peaks may be smaller or larger depending on the original item.

![Audio bars on Audacity](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingCassetteTapes-271122-0153-14_Page_6_Image_0001.jpg)

- Save your file to your source media by going to the Audacity toolbar, clicking __File__, selecting __Export__ from the menu, and then __Export as WAV__.  
- When you save the file, a window will appear for you to enter metadata (description info) about the file. If desired, include how the file was digitized and who owns the rights to the recording. This information will be embedded into the file and can be viewed by viewing the file’s properties in the future. Name the file something that indicates information about the cassette, such as the creator, title, or date cassette was recorded or published. 

![Metadata screen in Audacity](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/WL-DigitizingCassetteTapes-271122-0153-14_Page_6_Image_0002.jpg)

- If you are uploading to a cloud location, such as OneDrive, save to the desktop and then upload to the cloud location of your choice. Once you have verified the file is uploaded, be sure to delete the file from the desktop.  
- If there is content on Side B/Side 2 of the disc, press the __Stop__ button in Audacity (seen below). Lift the cue lever and move the tone arm back to the arm rest. Press __Start/Stop__ on the record player.

![Stop button in Audacity](https://elizajames.github.io/digital-preservation-documentation/assets/images/digitization/StopButton.png)

- Flip the record to where Side B/Side 2 is facing up and repeat the relevant __physical setup__, __capture__, and __saving__ process outlined on this page. Sometimes there is no content on Side B/Side 2. Once finished, remove the red and white cables from the front of the __Roland sound interface__ (being sure to leave the adapters plugged into the interface) and clip them on the wall where they were originally placed.