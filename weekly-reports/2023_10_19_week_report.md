# Report 8 - Week of 10/12/2023-10/19/2023 #
## Rachel Qingzhu Zhang

This week, we successfully completed our project! This project is exactly as CUTE as my project 1 (do you rememerber the kitten-head phonestand?): a pillow with a fish shape! What is more, it can create music (very nintendo-ish 8-bit electro music)! we use the sensor ADHL362 for the interaction part

The sensor provides six parameters: three axes for the accelerometer and three orientations (roll, pitch, and tilt) for the gyroscope. We utilize the accelerometer axes for rhythm generation, and the gyroscope's roll, pitch, and tilt for crafting melodies.

<img width="600" alt="10.5-a" src="https://github.com/Berkeley-MDes/tdf-fa23-Rachel-Qingzhu-Zhang/blob/main/weekly-reports/10.19-0.png">

Creating sound is not a difficult task. While creating music, especially to achieve harmony is more complicated, which requires a deeper understanding of music. Therefore, we explored basic music theory.

<img width="600" alt="10.5-a" src="https://github.com/Berkeley-MDes/tdf-fa23-Rachel-Qingzhu-Zhang/blob/main/weekly-reports/10.19-1.png">

In melody creation, the fundamental elements are notes, chords, and scales. A note is the basic unit, a set of notes forms a chord, and a progression of chords creates a scale. For appealing music, it's desirable to have notes structured into chords, with chord progressions adhering to a particular scale. We enriched our understanding of this by engaging with various resources on music theory.

<img width="600" alt="10.5-a" src="https://github.com/Berkeley-MDes/tdf-fa23-Rachel-Qingzhu-Zhang/blob/main/weekly-reports/10.19-2.png">

For music programming, we employed Max/MSP. Our primary function is to map each sensor value to the piano's range, which spans from 0 to 88. For instance, when working with the C Major scale, it's necessary to skip certain notes. Therefore, we performed a translation from our available notes to those within the C Major scale. This translation allows us to work with different scales, thereby enabling the creation of various musical styles.

The most challenging aspect involves transmitting data from the Photon to Max via Bluetooth. We opted for Bluetooth over Wi-Fi due to the latter's one-second delay. Using USB cables isn't a viable option while handling our pillow. The process of setting up Bluetooth proved more complex than anticipated. Thanks to Lingxiu's efforts, particularly in handling the technical aspects that involved numerous Python and terminal commands, we are now able to receive the data promptly.

(Bluetooth connection patch in Max)
<img width="600" alt="10.5-a" src="https://github.com/Berkeley-MDes/tdf-fa23-Rachel-Qingzhu-Zhang/blob/main/weekly-reports/10.19-3.png">


