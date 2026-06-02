# Usage Guide
## Installation
Nishiren Diffsinger is currently made to function on the OpenUTAU software. Downloading the latest beta version of the [official branch](https://github.com/stakira/OpenUtau) is recommended to use this voicebank. Errors may occur when not using the latest version of the software. The voicebank can be installed by dragging it onto the opened program, or by unzipping it in the “Singers” folder in OpenUTAU’s files.
## Using the Voicebank
Select Nishiren as the singer for a track. Be sure that their phonemizer is set correctly to one of the following:

**[DIFF]** used for both Kana and Pinyin inputs<br>
**[DIFF EN]** used for English, Kana(JA), and Hangul(KO) inputs<br>
**[DIFF JA]** used for Japanese (Kana+Romaji)<br>
**[DIFF ZH]** used for Mandarin (Hanzi+Pinyin)<br>
**[DIFF KO]** used for Korean (Hangul+Romaji)<br>
**[DIFF ES]** used for Spanish<br>
**[DIFF IT]** used for Italian<br>
**[DIFF FR MILLE]** used for French<br>
**[DIFF TH]*** used for Thai (*download from PrintMOV's site)

Note: Phonemizers may not always be perfect and additional phoneme editing may be recommended.

### Expressions
Diffsinger for OpenUTAU can only use curve expressions to edit the vocals. Expressions available to this voicebank are:

- __Gender (GENC):__ [default 0, min -100, max 100] Positive gender will give the vocals a lower, darker tone. Negative gender will give vocals a higher, brighter tone.
- __Velocity (VELC):__ [default 100, min 0, max 200] Increased velocity improve pronunciations in fast paced singing. Lower velocity may improve pronunciations for slower singing, but is not often recommended.
- __Tension (TENC):__ [default 0, min -100, max 100] Positive tension will make vocals sound stronger. Negative tension will make it sound gentler.
- __Breathiness (BREC):__ [default 0, min -100, max 100] Positive breathiness will make vocals sound breathy and airy. Negative breathiness will make it sound more breathless.
- __Voicing (VOIC):__ [default 0, min 0 (recommended: -100), max 100 (recommended: 200)] Be sure to change the default min and max to get the most out of this expression. Positive voicing will make vocals sound louder. Negative voicing will make it sound softer.
- __Tone Shift (SHFC):__ [default 0, min -1200, max 1200] Synthesizes the vocals up or down the shifted amount, then pitches the output to the intended pitch.

### Vocal modes
Voice colors (or vocal modes) can be set using the CLR expression or used as curve expressions to use them at certain percentages or to mix them together. To utilize vocal mode curves, go to the [Project] tab and select [Expressions...] then find the button near the bottom that says [Add all expressions suggested by renderers], then hit Apply. This will allow you to set the percentages of each vocal modes used from the curve expressions that can be selected at the bottom of the piano roll window.

Note: Vocal modes will always have a sum of 100%. Meaning that if the sum is less than 100%, it is complemented with the speaker specified in the CLR. If the sum is greater than 100%, its ratio is scaled down so that the sum equals 100% while maintaing the ratio of the voice colors.

Fun fact: Vocal modes can also be set to negative amounts by changing the minimum value to below zero. This can be used in creative ways, from reducing the specific tone of a voice color to creating unique tones not present from using the basic voice colors.

### Autopitch
Nishiren has a trained autopitch model based on the singing samples from their dataset. Autopitch will be applied to a section of connected notes. Right click a note in a section or selection, and go to Notes -> Load rendered pitch or use the shortcut ctrl+R.

**Warning**: Creator recommends generating pitch for one section at a time to avoid crashing the software. Long sections of connected notes may need to be cut into sections in order for pitch rendering to not crash the software.
