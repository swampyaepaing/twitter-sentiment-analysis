# Twitter Sentiment & Socioeconomic Status in NYC (2020)

**Collaborative Data Analytics Project · Masaryk University · June 2024**

**Project team:** Swam Pyae Paing, Mark Berezovskyi, Samuel Dribsa.

A computational social science study of sentiment in COVID-19-related tweets from New York City during 2020 and its observed association with neighbourhood income.

## Research questions

1. How were positive, negative and neutral sentiments distributed across the available tweets?
2. What geographic variation was visible in tweet sentiment by ZIP code?
3. How much of the variation in sentiment scores was explained by neighbourhood income in the fitted regression?

## Methods reported

- Python processing of COVID-19-related tweets, with **Dask** for larger datasets.
- Text cleaning, tokenization, stop-word removal and stemming.
- **TextBlob** sentiment scoring.
- ZIP-code sentiment visualization and matching to socioeconomic indicators.
- Linear regression and exploratory clustering with **K-means**.

## Key findings

The project report describes neutral sentiment as the largest category, with positive tweets slightly outnumbering negative tweets. The fitted simple regression reported an income coefficient of **−3.74905091 × 10⁻⁷** and **R² = 0.00135645**, so income explained only approximately **0.14%** of score variation in that fitted model.

**Important:** This is a weak descriptive association, not a meaningful predictive relationship or evidence of a causal effect. Geographic interpretations should also be treated cautiously, particularly where they appear stronger than the regression warrants.

## Research materials

- [Original project notebook on Google Colab](https://colab.research.google.com/drive/1dpvhGJbZ4-lti6kX3WQla_pM3SlyV4Dl?usp=sharing) (link recorded in the team report; access permissions may vary).
- The original team report was prepared in June 2024.
- Public reproduction instructions: [DATA_SOURCES.md](DATA_SOURCES.md).

## Limitations and research integrity

Social media users are not representative of the general population, ZIP-code matching may be incomplete, and lexicon-based sentiment models can misread irony, context and informal language. The team report and results belong to the named collaborators. The original large notebook references external Google Drive paths and has not yet been released here in a verified self-contained form.

**Status:** Public documentation, not yet a fully reproducible code repository.
