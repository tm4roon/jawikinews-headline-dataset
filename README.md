# Japanese Wikinews Headline Dataset
The datasets contain article-headline pairs obtained from [Japanese Wikinews](https://ja.wikinews.org/wiki/). 
The articles and headlines are segmented to words using [mecab-ipadic](https://taku910.github.io/mecab/).

In this repository, there are following three version datasets according to the article length:
- **full-articles**: the dataset with articles more than 10 tokens, and headlines;
- **long version**: the dataset with articles extracted from the first five sentences or 256 tokens, and headlines.
- **short version**: the dataset with articles extracted from the three sentences or 128 tokens, and headlines.


## Data Statistics
<p align="center">
Table1 Number of documents

|    dataset    |   # doc.    | Mean # words in articles | Mean # words in headlines |
| :-----------: | :---------: | :----------------------: | :-----------------------: |
| full-articles |    3,670    |           465.3          |           13.39           |
| long version  |    3,670    |           181.9          |           13.39           |
| short version |    3,589    |           93.79          |           13.33           |
</p>

<br>
<br>

<p align="center">
Table2 N-gram overlaps in headline

|    dataset    | uni-gram [%] | bi-gram [%] | tri-gram [%] | 4-gram [%] |
| :-----------: | :----------: | :---------: | :----------: | :--------: |
| full-articles |    93.43     |    52.02    |    30.75     |   17.75    |
| long version  |    86.73     |    37.48    |    19.33     |   10.15    |
| Short version |    80.79     |    32.20    |    16.34     |   8.246    |
</p>
