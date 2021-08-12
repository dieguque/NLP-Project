# Apple opinion on twitter users
Diego Duque

### Question/need:

* What is the framing question of your analysis, or the purpose of the model/system you plan to build? 

Twitter users sentiment text related to Apple.

* Who benefits from exploring this question or building this model/system?

Apple board and stockholders.

### Data Description:

* What dataset(s) do you plan to use, and how will you obtain the data?

This public [Kaggle](https://www.kaggle.com/seriousran/appletwittersentimenttexts) dataset.

* What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? 

All the features will be used: 1624 unique values and 3 columns (-1: negative, 0: neutral, 1: positive).

* If modeling, what will you predict as your target?

For modeling the columns 1 that indicates positive sentiment text will be used.

### Tools:

* How do you intend to meet the tools requirement of the project? 

Tokenizer
sklearn
Feature Extraction
from sklearn.feature_extraction.text import TfidfVectorizer, ENGLISH_STOP_WORDS
Topic Modeling
from sklearn.decomposition import NMF, TruncatedSVD, LatentDirichletAllocation
NLTK VADER (sentiment analysis)

* Are you planning in advance to need or use additional tools beyond those required?

No for now.

#### MVP Goal:

* What would a [minimum viable product (MVP)](./mvp.md) look like for this project?

Get some prelimiary analysis about if it's viable to find any related sentiment text to Apple with this dataset.
