# Extra Experiments
Currently 2 experimental phoneme sets are included in Nishiren's model. These are very lightly implemented just for fun.

## Saxophone (sax/)
Parallel trained from Gardanana's saxophone recordings. Nishiren will do their best to imitate a saxophone. Can be used with the [DIFFS] phonemizer, using the following:
| Input | Phonemes |  |
| :---: | :---: | :---: |
| leg | [sax/a] | Legato note |
| stacc | [sax/st, sax/a] | Stacatto note |
| honk | [sax/hx, sax/a] | Breathy attack note |
| growl | [sax/gr] | Growly note |
| hx | [sax/hx] | Breathy sound |

## Beatbox (bb/)
Vocal percussion. Can be used with any phonemizer, using the following:
| Input | Phoneme |  |
| :---: | :---: | :---: |
| ki_b | [bb/ki_b] | Kick drum, B sound |
| ki_bf | [bb/ki_bf] | Kick drum, B sound with F release |
| ki_p | [bb/ki_p] | Kick drum, P sound |
| ki_psh | [bb/ki_psh] | Kick drum, P sound with SH release |
| sn_k | [bb/sn_k] | Snare drum, K sound |
| sn_p | [bb/sn_p] | Snare drum, P sound |
| sn_pf | [bb/sn_pf] | Snare drum, P sound with F release |
| sn_psh | [bb/sn_psh] | Snare drum, P sound with SH release |
| ht_k | [bb/ht_k] | Hi-hat, K sound |
| ht_p | [bb/ht_p] | Hi-hat, P sound |
| ht_t | [bb/ht_t] | Hi-hat, T |
| ht_tt | [bb/ht_tt] | Hi-hat, long TS sound |
| bs_th | [bb/bs_th] | Throat bass |
| FF | [bb/f] | Rhythmic fricative |
| clck | [bb/clck] | Tongue click |
