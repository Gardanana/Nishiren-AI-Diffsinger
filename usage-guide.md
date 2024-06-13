# Usage Guide
## Installation
Nishiren Diffsinger is currently made to function on the OpenUTAU software. The latest beta version of the [official branch](https://github.com/stakira/OpenUtau), or the [diffsinger branch](https://github.com/xunmengshe/OpenUtau) (creator recommended) can be downloaded to use the voicebank. Errors may occur when not using the latest version of the software. The voicebank can be installed by dragging it onto the opened program, or by unzipping it in the “Singers” folder in OpenUTAU’s files.
## Using the Voicebank
Select Nishiren as a singer to a track. Be sure that their phonemizer is set to the target language.

[DIFF] used for both Kana and Pinyin inputs<br>
[DIFF EN] used for both English and Kana inputs<br>
[DIFF JA] used for Japanese (Kana+Romaji)<br>
[DIFF ZH] used for Mandarin (Pinyin+Hanzi)<br>
[DIFF ES] used for Spanish<br>
[DIFF FR]* used for French (*download from UFR)

Note: Phonemizers may not always be perfect, and additional phoneme editing may be needed.

### Expressions
Diffsinger for OpenUTAU can only use curve expressions to ___. Expressions available are:

- Gender (GENC): [default 0, min -100, max 100] Positive gender will give the vocals a lower, darker tone. Negative gender will give vocals a higher, brighter tone.
- Velocity (VELC): [default 100, min 0, max 200] Increased velocity improve pronunciations in fast paced singing. Lower velocity may improve pronunciations for slower singing, but is not often recommended.
- Tension (TENC): [default 0, min -100, max 100] Positive tension will make vocals sound stronger. Negative tension will make it sound softer.

To utilize vocal mode curves, go to the [Project] tab and select Expressions... -> Add all expressions suggested by renderers, then hit Apply. This will allow you to set percentages of vocal modes used by using curves that can be selected at the bottom of the piano roll window.

Note: Vocal modes will always have a sum of 100%. Meaning that if the sum is less than 100%, it is complemented with the speaker specified in the CLR. If the sum is greater than 100%, it is scaled down so that the sum equals 100%.

### Autopitch
Nishiren has a trained autopitch model based on the singing samples from their dataset. Autopitch will be applied to a section of connected notes. Right click a note in this section and go to Notes -> Load rendered pitch.

**Warning**: Creator recommends generating pitch for one section at a time to avoid crashing the software. Long sections of connected notes may need to be cut into section in order for pitch rendering to not crash the software.
