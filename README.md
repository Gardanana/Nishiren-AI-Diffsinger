![header image](/image/cover.png)
*illust by [ポメポメ](https://x.com/morinopome2)*

Nishiren Gard (西蓮ガルド) is a vocal synth that can sing using Diffsinger for OpenUTAU. They have a contralto voice with a youthful and versatile tone that can easily be adjusted to fit a wide variety of music. Nishiren sings primarily in English and Japanese, but can also sing in a few additional languages.

Voicer/Manager: Gardanana<br>
Official Site: https://gardanana.neocities.org/

<br>

[DOWNLOAD LATEST (v2.0)](https://github.com/Gardanana/Nishiren-AI-Diffsinger/releases/tag/v2.0)<br>
By downloading this voicebank you agree to their [Terms of Service](/terms-of-service.md)

For details on installing and using the voicebank, check out the [Usage Guide](/usage-guide.md)
# TECHNICAL INFORMATION
Range: Contralto (A2-A5)<br>
Microphones: Samson Go, AT2020USB+, Neumann U87<br>
Available Parameters: gender (GENC), velocity (VELC), tension (TENC), breathiness (BREC), voicing (VOIC), autopitch<br>
Recorded Languages: English, Japanese<br>
XLS: Mandarin Chinese, Korean, Spanish, Italian, French, Thai

### Phonemizers:
[DIFF] used for both Kana and Pinyin inputs<br>
[DIFF EN] used for English, Kana(JA), and Hangul(KO) inputs<br>
[DIFF JA] used for Japanese (Kana+Romaji)<br>
[DIFF ZH] used for Mandarin (Hanzi+Pinyin)<br>
[DIFF KO] used for Korean (Hangul+Romaji)<br>
[DIFF ES] used for Spanish<br>
[DIFF IT] used for Italian<br>
[DIFF FR MILLE] used for French<br>
[DIFF TH]* used for Thai (*[DL here](https://github.com/printto/diffs_th_plugin))

Extra phonemes: [exh], [axh] for exhales<br>
	  [gs] glotal stops, [cl] closures, [vf] vocal fry

[Full phoneme chart](/phoneme-chart.md)

### Vocal modes (and Dataset Info):
- Standard (55 min): Standard tone for Nishiren. 
- Power (9 min): Stronger and aggressive tone
- Soft (13 min): Darker and gentler tone. Use with adjusted variance parameters to get a whispery voice
- Sweet (7 min): Upbeat and nasaly tone
- Emotional (5 min): Passionate and dramatic tone. Deeper sounding voice
- 2P (6 min): Kayama Gard's voice. Nasaly and strongly voice acted

Multispeaker public datasets: Amaboshi Cipher, OfutonP, PJS, TIGER, Opencpop, M4Singer, CSD, Gianloop's datasets, Ryoku, Petit Millefeuille, Printto TH Dataset

# SAMPLE
[![DEMO](https://img.youtube.com/vi/Y13BWpI8-wM/0.jpg)](https://www.youtube.com/watch?v=Y13BWpI8-wM)

# CHANGELOG
- **v2.0** - Switch to multi-dict. Added Korean, Italian, and Thai. Added new Emotional vocal mode. Added breathiness and voicing parameters. Improved sound quality using muon+lynxnet2
- **v1.2** - New pitch model using lynxnet. Edited English dictionary with more pronunciation corrections. Finetuned PC-NSF-Hifigan vocoder
- **v1.1** - Retrained acoustic and tension with VR. Exported vocoder with mel base e to increase inference speed. Switched f0 extractor from parselmouth to rmvpe, and accelerator to unipc. Recording data added
- **v1.02** - Fixed dsdict-ja
- **v1.01** - dsvariance file patch
- **v1.0** - Full release. Trained with reflow, switched from energy + breathiness to tension, new recording data, added XLS (Mandarin, Spanish, French)
- **v0.11** - Updated vocoder
- **v0.1** - Initial beta release

# CONTACT
For any questions or feedback, please contact Gardanana

- Discord: gardanana<br>
- Twitter: [@gardanana582](https://twitter.com/gardanana582)<br>
- Tumblr: [@gardanana](https://gardanana.tumblr.com/)<br>
- Youtube: [@Gardanana](https://www.youtube.com/@Gardanana)
