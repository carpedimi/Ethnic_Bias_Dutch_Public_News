# Ethnic_Bias_Dutch_Public_News
Investigation of ethnic bias within the Dutch public news outlet's coverage

The notebooks in this repository are responsible for investigating the research questions: 
How do stereotypes differ in non-western ethnicities compared to western and native ethnicities? 
& 
How do sentiment distributions differ within articles that contain non-western ethnic names compared to articles that contain native and western ethnic names?

If you would like to run the code, the necessary folder can be downloader from: https://www.sendbig.com/view-files/?Id=d0889f38-bcff-c8cc-653c-029e7d1a7f65
The downloadable link is valied from first of July 2022 until 31st of July 2022.

When downloading the link, assure the following folder structure:
├── dutch-news-articles.csv

├── NOS.wordvectors.vectors.npy

├── NRC-Emotion-Lexicon

│   ├── NRC - Sentiment Lexicon - Research EULA Sept 2017 .pdf

│   ├── README.txt

│   ├── EmoLex-Ethics-Data-Statement.pdf
│   ├── .DS_Store
│   └── NRC-Emotion-Lexicon-v0.92
│       ├── NRC-Emotion-Lexicon-v0.92-In105Languages-Nov2017Translations.xlsx
│       ├── Paper1_NRC_Emotion_Lexicon.pdf
│       ├── Paper2_NRC_Emotion_Lexicon.pdf
│       ├── Paper3-EthicalConsiderations.pdf
│       ├── NRC-Emotion-Lexicon-Wordlevel-v0.92.txt
│       ├── NRC-Emotion-Lexicon-Senselevel-v0.92.txt
│       ├── .DS_Store
│       ├── readme.txt
│       ├── ~$NRC-Emotion-Lexicon-v0.92-In105Languages-Nov2017Translations.xlsx
│       └── Older Versions
│           ├── NRC-Emotion-Lexicon-v0.92-InManyLanguages.xlsx
│           └── readme.txt
├── NOS_CBOW_10W_100D.wordvectors
├── nos_news_complete.csv
├── ethnic_name_list.csv
├── nosnews_complete_with_sentiment.csv
├── ethnic_subsets
│   ├── netherlands_nosnews.csv
│   ├── italy_nosnews.csv
│   ├── greece_nosnews.csv
│   ├── iran_nosnews.csv
│   ├── morocco_nosnews.csv
│   ├── turkey_nosnews.csv
│   ├── syria_nosnews.csv
│   ├── somalia_nosnews.csv
│   ├── afghanistan_nosnews.csv
│   ├── outgroups_nosnews.csv
│   └── ingroups_nosnews.csv
├── plots_and_tables
│   ├── sentiment_descriptives.csv
│   ├── HT_descriptives.csv
│   ├── names_included_per_country.csv
│   ├── LS_descriptives.csv
│   ├── shapiro_table_HT.csv
│   ├── grouped_names_per_country_whole_corpus.csv
│   ├── shapiro_table_LS.csv
│   ├── grouped_names_per_country.csv
│   ├── scatterplot_LS_HT.png
│   ├── shapiro_table_sent.csv
│   ├── Sentiment_bPlots.png
│   ├── Sentiment_bPlots_second.png
│   ├── Sentiment_bPlots_Positive.png
│   └── Sentiment_bPlots_first.png
├── nosnews_sections
│   ├── fileBinnenland.csv
│   ├── fileBuitenland.csv
│   ├── fileCultuur & Media.csv
│   ├── fileEconomie.csv
│   ├── fileKoningshuis.csv
│   ├── fileOpmerkelijk.csv
│   ├── filePolitiek.csv
│   ├── fileRegionaal nieuws.csv
│   └── fileTech.csv
├── notebook_thesis_tidy.ipynb
└── ethnic_names_scrape.ipynb
