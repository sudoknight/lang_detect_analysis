## Language Detection and Analysis of very short sentences

When the input sentence is too short, the language detection models and libraries often stuggle to predict the correct language. This short analysis 

This short analysis is done in order to check whether the language detection performed by fasttext model is better than the previosuly detected languges in the dataset or not and How does fasttext model perform on short-sentences or words.

#### Dataset
Hotel Reviews dataset. Most of the sentences are made up of one or two words.

**Columns:**
- prev_detected_lang: Language detected by the reviewing platform. It contains alot of wrong values.
- text: review text

#### Models: 
fastText language detection model (with 217 languages).


