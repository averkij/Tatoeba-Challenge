# opus1m+bt-2021-04-10.zip

* dataset: opus1m+bt
* model: transformer-align
* source language(s): eng
* target language(s): dsb hsb
* model: transformer-align
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* valid language labels: >>dsb<< >>hsb<<
* download: [opus1m+bt-2021-04-10.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-wen/opus1m+bt-2021-04-10.zip)
* test set translations: [opus1m+bt-2021-04-10.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-wen/opus1m+bt-2021-04-10.test.txt)
* test set scores: [opus1m+bt-2021-04-10.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-wen/opus1m+bt-2021-04-10.eval.txt)

## Benchmarks

| testset | BLEU  | chr-F | #sent | #words | BP |
|---------|-------|-------|-------|--------|----|
| Tatoeba-test.eng-dsb 	| 10.5 	| 0.296 	| 34 	| 184 	| 1.000 |
| Tatoeba-test.eng-hsb 	| 11.1 	| 0.345 	| 40 	| 207 	| 1.000 |
| Tatoeba-test.eng-multi 	| 10.8 	| 0.322 	| 74 	| 391 	| 1.000 |

