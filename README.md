![header image](/image/cover.png)
*illust by [ポメポメ](https://x.com/morinopome2)*

Nishiren Gard (西蓮ガルド) is a vocal synth that can sing using Diffsinger for OpenUTAU. They have a contralto voice with a youthful and versatile tone that can easily be adjusted to fit a wide variety of music. Nishiren sings mainly in English and Japanese, but can also be used with a couple of additional languages.

Voicer/Manager: Gardanana<br>
Official Site: https://gardanana.neocities.org/

<br>

[DOWNLOAD LATEST (v1.1)](https://github.com/Gardanana/Nishiren-AI-Diffsinger/releases/tag/v1.1)<br>
By downloading this voicebank you agree to their [Terms of Service](/terms-of-service.md)

For details on installing and using the voicebank, check out the [Usage Guide](/usage-guide.md)
# TECHNICAL INFORMATION
Range: Contralto (A2-F5)<br>
Microphones: Samson Go, AT2020USB+<br>
Available Parameters: gender (GENC), velocity (VELC), tension (TENC), autopitch<br>
Recorded Languages: English, Japanese<br>
XLS: Mandarin Chinese, Spanish, French

### Phonemizers:
[DIFF] used for both Kana and Pinyin inputs<br>
[DIFF EN] used for both English and Kana inputs<br>
[DIFF JA] used for Japanese (Kana+Romaji)<br>
[DIFF ZH] used for Mandarin (Pinyin+Hanzi)<br>
[DIFF ES] used for Spanish<br>
[DIFF FR]* used for French (*download from [UFR](https://github.com/imsupposedto/Millefeuille-DiffSinger-French))

Extra phonemes: [exh], [axh] for exhales<br>
	  [q] glotal stops, [cl] closures, [vf] vocal fry

[Full phoneme chart](/phoneme-chart.md)

### Vocal modes (and Dataset Info):
- Standard (50 min): Standard tone for Nishiren. 
- Power (7 min): Stronger and deeper tone
- Sweet (6 min): Upbeat, nasaly tone
- Soft (10 min): Darker tone. Use with tension to get a whispery voice
- 2P (8 min): Kayama Gard's voice. Nasaly and strongly voice acted

Multispeaker trained with: Namine Ritsu, OfutonP, PJS, Alex Floarea, TIGER, Opencpop, M4Singer, Tiny Italian Spanish Dataset, Namine Criss, Petit Millefeuille

# SAMPLE
[![DEMO](https://img.youtube.com/vi/Y13BWpI8-wM/0.jpg)](https://www.youtube.com/watch?v=Y13BWpI8-wM)

# CHANGELOG
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
