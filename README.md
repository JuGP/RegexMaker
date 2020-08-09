# RegexMaker
What is it?
------------
This script dynamically generates a regex given a sentence.

Specification
------------
* Allow a word to be typed both in the plural and in the singular (this processing was based on the RSLP Stemmer algorithm (Removedor de Sufixos da Lingua Portuguesa);
* Allows an accentuation to be confused or even forgotten;
* Allows punctuations to be typed optionally;
* Allows stopwords (words that contribute little to the general meaning of a text) to be typed optionally.

Requirements
------------
The following modules are required to run the code:
* [NLTK](https://www.nltk.org/)
