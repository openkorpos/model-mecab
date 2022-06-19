# model-mecab
MeCab model trained with OpenKorPos.

# Using with Konlpy
To use this model with Konlpy, you simply need to construct
a Mecab tagger with the path to this repository.

```python
from konlpy.tag import Mecab
m = Mecab('mecab-model')

m.pos('분석할 텍스트입니다.')
```
