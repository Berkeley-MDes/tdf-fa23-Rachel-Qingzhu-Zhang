# Report 8 - Week of 10/12/2023-10/19/2023 #
## Rachel Qingzhu Zhang

The sensor provides six parameters: three axes for the accelerometer and three orientations (roll, pitch, and tilt) for the gyroscope. We utilize the accelerometer axes for rhythm generation, and the gyroscope's roll, pitch, and tilt for crafting melodies.

<img width="700" alt="10.5-a" src="https://github.com/Berkeley-MDes/tdf-fa23-Rachel-Qingzhu-Zhang/blob/main/weekly-reports/10.5-a.png">

Creating music is a nuanced task. While it's relatively straightforward for a device to produce sound, crafting musical pieces requires a deeper understanding, especially to achieve harmony. Therefore, we explored basic music theory.

<img width="700" alt="10.5-a" src="https://github.com/Berkeley-MDes/tdf-fa23-Rachel-Qingzhu-Zhang/blob/main/weekly-reports/10.5-a.png">

In melody creation, the fundamental elements are notes, chords, and scales. A note is the basic unit, a set of notes forms a chord, and a progression of chords creates a scale. For appealing music, it's desirable to have notes structured into chords, with chord progressions adhering to a particular scale. We enriched our understanding of this by engaging with various resources on music theory.

<img width="700" alt="10.5-a" src="https://github.com/Berkeley-MDes/tdf-fa23-Rachel-Qingzhu-Zhang/blob/main/weekly-reports/10.5-a.png">

For music programming, we employed Max/MSP. Our primary function is to map each sensor value to the piano's range, which spans from 0 to 88. For instance, when working with the C Major scale, it's necessary to skip certain notes. Therefore, we performed a translation from our available notes to those within the C Major scale. This translation allows us to work with different scales, thereby enabling the creation of various musical styles.

<img width="700" alt="10.5-a" src="https://github.com/Berkeley-MDes/tdf-fa23-Rachel-Qingzhu-Zhang/blob/main/weekly-reports/10.5-a.png">


