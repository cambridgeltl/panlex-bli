# PanLex-based bilingual lexicons for 210 language pairs (15 languages)

Contact: [Ivan Vulić](https://sites.google.com/site/ivanvulic/) (iv250 AT cam DOT ac DOT uk)

This repo contains bilingual lexicons for 210 language pairs (15 languages in total) used in the empirical comparison paper [Do We Really Need Fully Unsupervised Cross-Lingual Embeddings?](https://arxiv.org/pdf/1909.01638.pdf) (Vulić et al., EMNLP 2019)

The bilingual lexicons have been extracted from the [PanLex](https://panlex.org/) database of translations: more details on the extraction procedure are provided in the paper.


### References

If you use these lexicons in your own work, please cite the following paper:
```
@inproceedings{Vulic:2019clwe,
  author    = {Vuli\'{c}, Ivan and Glava\v{s}, Goran and Reichart, Roi and Korhonen, Anna},
  title     = {Do We Really Need Fully Unsupervised Cross-Lingual Embeddings?},
  booktitle = {Proceedings of the 2019 Conference 
              on Empirical Methods in Natural Language Processing (EMNLP)},
  year      = {2019},
  }
```

Please also acknowledge the use of PanLex by citing the following paper:
```
@inproceedings{Kamholz:2014panlex,
  author    = {David Kamholz and Jonathan Pool and Susan M. Colowick},
  title     = {{PanLex: B}uilding a Resource for Panlingual Lexical Translation},
  booktitle = {Proceedings of the 9th International Conference 
              on Language Resources and Evaluation (LREC)},
  pages     = {3145--3150},
  year      = {2014},
  }
```

### Languages and Lexicons

The following 15 languages are currently covered in the repo. For each language X, we provide a separate zip archive where X is the source language (L<sub>1</sub>) paired with the remaining 14 target (L<sub>2</sub>) languages.

* Bulgarian (bg): [bg-L<sub>2</sub>](https://github.com/cambridgeltl/panlex-bli/raw/master/lexicons/bg-l2-dicts.zip)
* Catalan (ca): [ca-L<sub>2</sub>]
* Esperanto (eo): [eo-L<sub>2</sub>]
* Estonian (et): [et-L<sub>2</sub>]
* Basque (eu): [eu-L<sub>2</sub>]
* Finnish (fi): [fi-L<sub>2</sub>]
* Hebrew (he): [he-L<sub>2</sub>]
* Hungarian (hu): [hu-L<sub>2</sub>]
* Indonesian (id): [id-L<sub>2</sub>]
* Georgian (ka): [ka-L<sub>2</sub>]
* Korean (ko): [ko-L<sub>2</sub>]
* Lithuanian (lt): [lt-L<sub>2</sub>]
* Norwegian Bokmål (no): [no-L<sub>2</sub>]
* Thai (th): [th-L<sub>2</sub>]
* Turkish (tr): [tr-L<sub>2</sub>]

If you want to download the entire bundle at once, please click [here]

### Some (Important) Remarks:

* The format of the lexicons should be self-explanatory. We provide training lexicons of different size N (N = 5000, 2000, 1000, 500).

* The provided lexicons are of course not perfect and have not been manually cleaned or verified although the extraction process from PanLex was quite strict in order to focus on high precision. Still, there might be some noise in the lexicons. Therefore, the lexicons should be considered as silver standard.

* For some language pairs (due to the strict extraction process), the number of pairs in the lexicons is smaller than the desired 5K training pairs or 2K test pairs - please double-check before running any size-related analyses of the lexicons and projection-based methods.

* For any further questions, please contact [Ivan Vulić](https://sites.google.com/site/ivanvulic/) (iv250 AT cam DOT ac DOT uk)

