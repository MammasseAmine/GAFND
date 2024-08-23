# GAFND
The Global Arabic Fake News Dataset (GAFND) is a comprehensive and unified resource designed to enhance fake news detection in the Arabic-speaking world. This dataset integrates and preprocesses three existing datasets: AFND, ANS, and AraFacts.

# Dataset Description

**Size:** Over 380,000 entries  
**Format:** CSV  
**Languages:** Arabic  
**Sources:** Various Arabic news websites, fact-checking platforms, and media outlets

## Features

- **Text:** Combined title and article text
- **Label:** Binary classification (0 for credible, 1 for not credible)
- **URL Count:** Number of URLs in the text
- **Stopword Count:** Number of stopwords removed
- **Emoji Count:** Number of emojis in the text
- **Special Character Count:** Number of non-Arabic characters

## Data Preprocessing

The dataset undergoes extensive preprocessing, including:

- URL removal
- Text normalization
- Punctuation removal
- Tashkeel and Tatweel removal
- Currency symbol conversion
- Number-to-Arabic word conversion
- Emoji replacement
- Stopword removal
- Non-Arabic character removal

# Data Visualization
Below are visual representations of various aspects of the dataset.

<details>
  <summary>Label Distribution</summary>
![Label Distribution]([path/to/label_distribution.png](https://github.com/MammasseAmine/GAFND/blob/main/EDA/Label%20Distribution.png?raw=true))
</details>

## Usage

You can access and download the dataset from the following link:  
<img src="https://github.com/MammasseAmine/GAFND/blob/main/EDA/Label%20Distribution.png?raw=true">

[Provide instructions on how to load and use the dataset]

## Citation

If you use this dataset in your research, please cite:  
```bibtex
@article{amine_creating_nodate,
  title = {Creating a Global Arabic Fake News Dataset},
  abstract = {The viral spread of misinformation in our interconnected world threatens the fabric of social trust and undermines the integrity of public perception, particularly in the Arabic-speaking world where resources for combating misinformation are limited. To address this challenge, we introduce the Global Arabic Fake News Dataset (GAFND), a comprehensive and unified dataset designed to enhance fake news detection in Arabic contexts. We combine three existing datasets—AFND, ANS, and AraFacts to create a larger, more diverse, and high-quality resource that captures the linguistic and cultural nuances of Arabic fake news. This combination is essential to overcome the limitations of individual datasets, such as size, diversity, and representation, which can lead to biased and inaccurate models. The resulting dataset comprises over 380,000 entries, enriched with features such as URL count, stopword count, emoji count, and special character count, facilitating nuanced analysis and improving detection performance. GAFND represents a significant step forward in Arabic fake news detection research, ultimately contributing to the fight against misinformation and supporting media literacy in Arabic-speaking communities.},
  language = {en},
  author = {Amine, MAMMASSE and Bedjou, Khaled and Azouaou, Faical},
}
```
## License

[Specify the license under which the dataset is released]

## Contact

mammasse@estin.dz

## Acknowledgments

This dataset is based on the following source datasets:

- **AFND (Arabic Fake News Dataset)**
- **ANS (Arabic News Stance)**
- **AraFacts**

We thank the creators of these datasets for their valuable contributions to Arabic NLP research.
