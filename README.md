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
</p>

<p align="center">
<img src=https://user-images.githubusercontent.com/53220859/65479667-50fc1000-dec9-11e9-93d2-b614e6ce930b.png>
</p>


<p align="center">
Table2 N-gram overlaps in headline
</p>

<p align="center">
<img src=https://user-images.githubusercontent.com/53220859/65479670-52c5d380-dec9-11e9-8b0a-5600f18b749c.png>
</p>
