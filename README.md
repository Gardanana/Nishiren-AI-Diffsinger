![header image](/image/cover.png)
*illust by [ポメポメ](https://x.com/morinopome2)*

Nishiren Gard (西蓮ガルド) is a singing vocal synth made with Diffsinger. They have a contralto voice with a youthful and versatile tone that can easily be adjusted to fit a wide variety of music. Nishiren was recorded natively in English and Japanese, but can sing in many additional languages through cross lingual synthesis (XLS).

Voicer/Manager: Gardanana<br>
Official Site: https://gardanana.neocities.org/

<br>

[DOWNLOAD LATEST (v2.1)](https://github.com/Gardanana/Nishiren-AI-Diffsinger/releases/tag/v2.1)<br>
By downloading this voicebank you agree to their [Terms of Service](/terms-of-service.md)

For details on installing and using the voicebank, check out the [Usage Guide](/usage-guide.md)
# TECHNICAL INFORMATION
Range: Contralto (G3-D5)<br>
Microphones: Samson Go, AT2020USB+, Neumann U87<br>
Available Parameters: gender (GENC), velocity (VELC), tension (TENC), breathiness (BREC), voicing (VOIC), autopitch<br>
Recorded Languages: English, Japanese<br>
XLS: Mandarin Chinese, Korean, Thai, Indonesian, Tagalog, Spanish, Italian, Brazilian Portuguese, French, German, Russian

### Phonemizers:
[DIFFS] used for both Kana and Pinyin inputs<br>
[DIFFS EN] used for English, Kana(JA), and Hangul(KO) inputs<br>
[DIFFS JA] used for Japanese (Kana+Romaji)<br>
[DIFFS ZH] used for Mandarin (Hanzi+Pinyin)<br>
[DIFFS KO] used for Korean (Hangul+Romaji)<br>
[DIFFS TH]* used for Thai (\*[Phonemizer from PRINTmov](https://github.com/printto/diffs_th_plugin))<br>
[DIFFS ID]* used for Indonesian (\*[Phonemizer from PRINTmov](https://github.com/printto/diffs_th_plugin))<br>
[DIFFS FIL] used for Filipino/Tagalog. Works best using the rule-based Filipino version.<br>
[DIFFS ES] used for Spanish<br>
[DIFFS IT] used for Italian<br>
[DIFFS BRAPA]* used for Brazilian Portuguese (*[Phonemizer from Team BRAPA](https://github.com/Team-BRAPA))<br>
[DIFFS FR MILLE] used for French<br>
[DIFFS DE MARZ] used for German<br>
[DIFFS RU] used for Russian<br>

Extra phonemes: [exh], [axh] for exhales<br>
	  [gs] glotal stops, [cl] closures, [vf] vocal fry
	  

### Vocal modes (and Dataset Info):
- Standard (60 min): Standard tone for Nishiren. 
- Power (9 min): Stronger and aggressive tone
- Soft (14 min): Darker and gentler tone. Use with adjusted variance parameters to get a whispery voice
- Sweet (10 min): Upbeat and nasal tone
- Emotional (5 min): Passionate and dramatic tone. Deeper sounding voice
- Screamo (4 min): Breathy and growly screamo vocals. Usually requires variance parameter editing to function properly (high tension + high breathiness)
- 2P (6 min): Voice of Kayama Gard, Nishiren's [2P](https://fanlore.org/wiki/2P) derivative. Nasal and strongly voice acted

Multispeaker public datasets: PJS, NIT070, OfutonP, TIGER, Hitsune Kumi, TREi, M4Singer, CSD, Mechol, Printto TH Dataset, Tiny Tagalog Dataset, Gianloop's datasets, Namine Ryoku, BRAPINHA, Petit Millefeuille, SSPCD, Daichi Yoshida, beatboxset1

### Extra Experiments:
Currently 2 experimental phoneme sets are included in Nishiren's model. These are very lightly implemented just for fun. Check [Experimental Phonemes](https://github.com/Gardanana/Nishiren-AI-Diffsinger/blob/main/phoneme-experimental.md) for more information on usage.

# SAMPLE
[![DEMO](https://img.youtube.com/vi/Y13BWpI8-wM/0.jpg)](https://www.youtube.com/watch?v=Y13BWpI8-wM)

# CHANGELOG
- **v2.1** - Added German, Russian, Brazilian Portuguese, Tagalog, and Indonesian. Added new Screamo vocal mode. Power vocal mode revamped. Various new recording data added. New vocoder finetuned on [Potluck Vocoder](https://github.com/mrtigermeat/potluck-vocoder). Accent improvement from mix-ln. Reduced file size.
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
- Email: gardanana582@gmail.com<br>
- Twitter: [@gardanana582](https://twitter.com/gardanana582)<br>
- Tumblr: [@gardanana](https://gardanana.tumblr.com/)<br>
- Youtube: [@Gardanana](https://www.youtube.com/@Gardanana)
