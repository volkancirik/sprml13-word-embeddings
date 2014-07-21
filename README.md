sprml13-word-embeddings
=======================
- A better and generalized version of this repository with new word vectors is at [here](https://github.com/ai-ku/wvec)




This repository contains word embeddings generated using [1] for a work [2] of the Shared Task of SPRML 2013.

- use german2.embeddings for better coverage. german.embeddings are
used in the SPRML'13 Shared Task submission.

- For english, we used WSJ 120M token corpus as LM corpus, and 1M Penn Treebank Corpus as
target corpus. They may have coverage problem. Use  [seed number]english50.embeddings or [seed number]english50+f.embeddings. The first one is extracted without morphologic and ortographic features. The second
one is extracted with morphologic and ortographic features.

If you use these word embeddings in your work you may want to cite:

[1]. Learning Syntactic Categories Using Paradigmatic Representations of Word Context, In Proceedings of the 2012 Conference on Empirical Methods in Natural Language Processing (EMNLP-CONLL 2012), Jeju, Korea, July. Association for Computational Linguistics, [Paper, Presentation & Code](http://www.denizyuret.com/2012/05/learning-syntactic-categories-using.html), [bib](http://aclweb.org/anthology/D/D12/D12-1086.bib). 

[2]. The AI-KU System at the SPMRL 2013 Shared Task : Unsupervised Features for Dependency Parsing, In Proceedings of the Fourth Workshop on Statistical Parsing of Morphologically-Rich Languages, pp 78--85, Seattle, Washington, USA, October. Association for Computational Linguistics, [Paper](http://aclweb.org/anthology//W/W13/W13-4909.pdf), [Word Embeddings](https://github.com/wolet/sprml13-word-embeddings), [bib](http://aclweb.org/anthology//W/W13/W13-4909.bib)


