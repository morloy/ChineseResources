# Chinese Character Decompositions

An easy to  read list of decompositions of Chinese characters.

[characterDecompositions.txt](distcharacterDecompositions.txt?raw=true)


Character decompositions are built from:
[CJK Decomposition Data](https://cjkdecomp.codeplex.com/)

Definitions and Mandarin Pronunciations:
[Unihan Database](http://unicode.org/charts/unihan.html)



An example entry look like:

```
載: 土 (tǔ) soil, earth; items made of earth / 戈 (gē) halberd, spear, lance; rad. 62 / 車 (chē) cart, vehicle; carry in cart
```

Thus, the file format is

```
Char: Component1 / Component2 / ...
```

whereas each component is given as

```
Char (MandarinPronunciation) Definition
```


The provided ipython notebook can be used to further customize the output.
All input files for generating this list are included in the repository.


# Classifiers

A list of "default" classifiers for each noun that requires one.
The goal is to treat each classifier like an article, very common in European languages, and associate each noun with a classifier.

An example entry is
```
裤子	条	tiáo	clause, condition; string, stripe
```
The third columns is the Pinyin reading of the classifier and the last columns gives a short definition.

There are two lists:
* [classifiers.txt](dist/classifiers.txt?raw=true)
* [classifiersAll.txt](dist/classifiersAll.txt?raw=true) (includes entries with 个)
