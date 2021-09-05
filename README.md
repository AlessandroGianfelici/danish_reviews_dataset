# Danish reviews dataset
A dataset of danish reviews to train sentiment classification models. 

This dataset has been collected from the internet using web scraping techniques. For further information take a look to the code:
```html
https://github.com/AlessandroGianfelici/trustpilot_spider.git
```


## Data

For each data point, the dataset contains the company name (hashed for privacy reasons), the title of the review, the text of the review and the number of stars (from 1 to 5). 


## Usage

The data are stored as a txt file with comma separated fields. For example, if you're using python you can load it with pandas:

```python
import pandas as pd

data = pd.read_csv('raw_data.txt')
```

