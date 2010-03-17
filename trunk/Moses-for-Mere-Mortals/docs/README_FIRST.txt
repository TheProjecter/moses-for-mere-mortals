README_FIRST (16/03/2010)

If you use a version more recent than Moses-for-Mere-Mortals-0.62.tar.gz, the previous trainings that you made can be used without changes. If you use Moses-for-Mere-Mortals-0.62.tar.gz or earlier, you will have to manually transfer your previous trainings to the new directory structure.

Relative to Moses-for-Mere-Mortals-0.62, the following main new features have been added:
1)	Removes control characters from the input files (these can crash a training);
2)	Extracts from the corpus files 2 test files by pseudorandomly selecting non-consecutive segments that are erased from the corpus files;
3)	A new training does not interfere with the files of a previous training;
4)	A new training reuses as much as possible the files created in previous trainings;
5)	Inversion of corpora (e.g., from en-pt to pt-en) detected, allowing a much quicker training than that of the original language pair;
6)	Can limit the duration of tuning;
7)	Get the BLEU and NIST scores of a translation (either for the whole document or for each segment of it);
8)	Transfer your trainings to someone else or to another Moses installation in the same computer;
9)	All the mkcls, GIZA and MGIZA parameters can now be controlled through parameters of the train-moses-irstlm-randlm script;
10)	Selected parameters of the Moses scripts and the Moses decoder can now be controlled through the train-moses-irstlm-randlm and translate-moses-irstlm-randlm scripts;
11)	Installs RandLM;
12)	Installs MGIZA;
13)	Implements distributed training with IRSTLM (so as to better manage memory);
14)	New make-test-moses-irstlm-randlm, score-moses-irstlm-randlm, and transfer-training-to-another-location-moses-irstlm-randlm scripts.
15)	Bigger demo corpus.
