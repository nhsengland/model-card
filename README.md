# NHS England Template Model Card

Welcome to the NHS England model card template! This README explains the purpose of a model card, it's design origins and what is included in this repository

## Purpose
The main purpose of a model card is to *standardise ethical practice and reporting*[^1] and is primarily geared towards aiding transparency around a models use of data and methods and it's resulting performance. Model cards are intended to be short documents that contain a range of non-technical and technical content for a variety of audiences - try to keep the content concise so it easily digestible by the reader. 

A model card is not a replacement for detailed documentation on quality assurance, testing, bias analysis and so on - these details should be included where relevant but kept to just the headline conclusions. Links to further documentation or analysis can be used to point people to more information.

[1]: Model cards for model reporting https://arxiv.org/pdf/1810.03993

By having a standardised template, creators of models can produce clear and open documentation, allowing for valuable scrutiny of solutions both internally and publicly.

This template can be copied into a new or existing repository and populated with information about the models that have been trained or that are in use in a system/service/algorithm. Storing the model card in a repository along with the code used to train, test and evaluate models will help to keep documentation up to date as both the model and it's documentation can be updated in parallel. It also enables easy publication of the model card into a public repository.


## Origins

The initial design and set-up of the model card template drew inspiration from both a [Google model card example](https://modelcards.withgoogle.com/object-detection) and [Kaggle](https://www.kaggle.com/code/var0101/model-cards). Both look to be inspired by [this research paper](https://arxiv.org/pdf/1810.03993) which was recommended in the UK Government's [Generative AI Framework for HMG](https://www.gov.uk/government/publications/generative-ai-framework-for-hmg/generative-ai-framework-for-hmg-html#:~:text=a%20particular%20person.-,Ethics,-The%20ethical%20questions) (published Jan 2024).  

[HuggingFace](https://huggingface.co/docs/hub/en/model-cards) also uses model cards, but examples of these are more focussed around the reusability of a model – where someone develops an open source model that can be fine tuned or embedded within an algorithmic tool/process - rather than models that are trained and then deployed into a live system.

## Content
The repo includes:

1. The model card template
    1. Specification
    2. Intended Use
    3. Data
    4. Methodology and Training
    5. Evaluation and Performance
2. An images folder where visualisations such as a confusion matrix can be stored for use in a model card

