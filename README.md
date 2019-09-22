# Japanese Wikinews Headline Dataset
**NOTE**: Work in Progress

This is a corpus of article-headline pairs extracted from Japanese Wikinews. 
The articles and headlines are segmented to words using [mecab-ipadic](https://taku910.github.io/mecab/).
There are following three datasets:
- **full-articles**: articles without filtering
- **long version**: articles filtered first five sentences or 256 tokens.
- **short version**: articles filtered first three sentences or 128 tokens.


## Data Statistics
Table # Number of documents

|    dataset    | # doc. | Mean # words |
| :-----------: | :----: | :----------: |
| full-articles |        |              |
| long version  |        |              |
| short version |        |              |
<br>
<br>

Table # N-gram overlaps in headline

|    dataset    | uni-gram [%] | bi-gram [%] | tri-gram [%] | 4-gram [%] |
| :-----------: | :----------: | :---------: | :----------: | :--------: |
| full-articles |    87.10     |    47.29    |    26.76     |   15.17    |
| long version  |    81.47     |    35.49    |    18.54     |   10.24    |
| Short version |    75.51     |    29.82    |    15.05     |   7.823    |




## Lisence

