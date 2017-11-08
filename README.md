# Audio_translator

This is work in progress and as such is a bare bone code. This code does the following

1. Listen to a sentence spoken (in english)
2. Creates a list of the spoken words
3. Translates to another language like French and creates a list of it.
4. Compiles the list into a sentence
5. Converts the text to speech in translated language
6. Plays the mp3 file created


Currently it translates from English to all the languages supported in [gTTS]('https://pypi.python.org/pypi/gTTS')
Currently works best while testing small phrases or words

TODO:
* Make it robust to support larger sentecses
* Add compatibility with other spoken languages in first step. Currently recognizes only English
* Improve time efficiency.
