# Music to Light Control
"Music to Light" is a feature that enables users to synchronize music bands (combination of the range of the frequencies) with the orbs.
> TODO: Create a YouTube video that describe the feature.

## Music To Light Control User Interface/Experience
Music to light control is located at the bottom-right corner of the screen.

![music-to-light-feature](https://user-images.githubusercontent.com/25746993/228419364-aefd6346-201c-4615-997d-87aa7585899d.png)

## Music to Light Controls

![image](https://user-images.githubusercontent.com/25746993/228414851-49825009-c42c-4083-9bbb-0002df86275f.png)

It consists of six sub-components to manage different settings in the feature:
1. [Music loader](#music-loader)
1. [Play, Pause, and Stop control](#play-pause-and-stop-control)
1. [Volume control](#volume-control)
1. [Music Synchronizer](#music-synchronizer)
1. [Playback control](#playback-control)

***

### Music loader
Music loader loads the music from the file. Right now only `.mp3` format is supported.

### Play, Pause, and Stop control
You can play, pause and stop the music. When you click the stop button, the music's cursor resets to the start.

### Volume control
Allows you to adjust the volume of the music.
> 📝 Note: This can also affect the intensity of the light.

### Music Synchronizer
Applies different synchronizing effects to the orbs. There are three effects:
1. Linear
1. Random
1. Amplitude

#### Linear effect
Applies current frequency of the each band of the music in the ordered manner to the selected orbs.

![music-to-light-linear](https://user-images.githubusercontent.com/25746993/228421112-69e79850-40b5-460b-997a-f114afd5a145.gif)

#### Random effect
Applies current frequency of the each band in the music randomly to the selected orbs. 

![music-to-light-random](https://user-images.githubusercontent.com/25746993/228421129-5d9ef2a2-3680-4637-8ec4-38d8d83e6e01.gif)

#### Amplitude effect
Applies overall current amplitude of the music to the selected orbs.
> 💡 Most common in music concerts.

![music-to-light-amplitude](https://user-images.githubusercontent.com/25746993/228421144-91426c1c-a7ea-4db1-9b59-7f340f2b63f1.gif)

### Playback control
Allows you to adjust the current cursor of the music and view the current and remaining play time of the music.
