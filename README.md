```python

from baidutrans import Translate

appid=''
secret=''

trans = Translate(appid, secret)

result = trans.trans('你好', 'en', 'auto')

print(result)
# hello
```