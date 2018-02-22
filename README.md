# Hebrew-Stopwords

List of Hebrew Stopwords for use in text analysis

## General Info

Created using the Hebrew Wikipedia as corpus (dump of 2018-02-01),
determined using normalized TF (-log(tf/v)).
Corpus shows heavy bias towards Israel related terms - keep in mind when using. Otherwise, feel free to use as you see fit.

### Example


```
import stopwords_heb
text = 'sample text'
stopwords = stopwords_heb.stopwords
for word in text:
  if word not in stopwords:
    print(word)
```
