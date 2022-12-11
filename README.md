# python-mecab-ko-dic
This is a version of[`mecab-ko-dic`](https://bitbucket.org/eunjeon/mecab-ko-dic) packaged for easy use in Python.  In order to use `mecab-ko-dic`, a complicated process of installing [`mecab-ko`](https://bitbucket.org/eunjeon/mecab-ko) and building the dictionary is required. This library performs these processes in advance and makes the built dictionary available just through installation.

## Credits
The dictionary was created by Yongwoon Lee and Yungho Yu as part of [the Eunjeon proejct](http://eunjeon.blogspot.com/).

## Usage
```python
import mecab_ko_dic
print("Dictionary path:", mecab_ko_dic.dictionary_path)
```