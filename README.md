# scaling-octo-bassoon
Dissertaion FYP Using language cues to detect clinical conditions

### Author
Ken Lok Chan 

## Setup 
Open the file in jupyter notebook and everything will be good to go

Please remember to install the module that is related into the desktop such as nltk,panda,sklearn and etc.

One thing to look out for would be the filepath for the related data.
```jupyter notebook
df = pd.read_csv("C:/Users/Chan Ken Lok/Documents/Dissertations/depression-detection/data/tweets_combined.csv")
pd.set_option('display.max_colwidth', 1)
```

in here the pd.read_csv would be needed to be change for the filepath.

Two files are in the src. One is a file with preprocessing method while other do not had the preprocessing method 

The data is based on https://github.com/swcwang/depression-detection, so you could check out the original data and coding from there
