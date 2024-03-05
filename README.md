# Mapping Global Protest Tendencies


This repository contains the code and data for the project "Mapping Global Protest Tendencies". 
This project has been conducted by **Jiyun Beak** at the [Industral Engineering department](https://gi.insa-lyon.fr/en/) of [INSA Lyon](https://www.insa-lyon.fr/en/) (National Institute of Applied Science of Lyon) under the supervision of [Ludovic Moncla](https://github.com/ludovicmoncla).


## Methodology

This study investigates the diverse manifestations of 'protest' across cultures and regions, aiming to provide a nuanced understanding of global dynamics and their impact on human rights. 
Utilizing topic modeling methods, we extract a substantial corpus of documents from the English Wikipedia, employing precise clustering techniques to categorize various types of protests based on semantic elements such as race, gender, and language. 
Through cartographic visualization, we illustrate the frequency and distribution of different protest topics. The primary goal is to identify geographic hotspots of human rights conflict, offering a detailed analysis of regional differences in protest propensity. 
This research serves as an initial step towards a comprehensive global understanding of protest dynamics and their implications for human rights worldwide.


List of notebooks: 
- [Data Collection](data_collection.ipynb)
- [Data Preprocessing](data_preprocessing.ipynb)
- [Topic Modeling](topic_modeling.ipynb)
- [Topic Mapping](topic_mapping.ipynb)
- [Topic Visualization](topic_visualization.ipynb)


## Results overview

[![Protest Topics](outputs/map_zeroshot_KeyBERTInspired_minsize50_minsimilarity0.8.png)](outputs/map_zeroshot_KeyBERTInspired_minsize50_minsimilarity0.8.png)


## Reproduce the experiment

### Configure a Python virtual environment

```bash
python -m pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

### (optionnal) Set the Environment Variable for the OpenAI API key

```bash
export OPENAI_API_KEY=<your_api_key>
```


## Cite this work

> Beak, J. and Moncla, L. (2024). Mapping Global Protest Tendencies: Geolocating Trends and Topics Through Wikipedia Analysis. In proceedings of the 2nd International Workshop on Geographic Information Extraction from Texts (GeoExT'24), ECIR Conference, Glasgow, UK.