# NHS England Template Model Card


## Purpose
The main purpose of a model card is to *standardise ethical practice and reporting*[^1] and is primarily geared towards aiding transparency around a model's use of data and methods and its resulting performance. Model cards are intended to be *short* documents that contain non-technical and technical content for a variety of audiences.

Model cards should be succinct, well-structured and easily digestible by the reader. A model card is *not a replacement for detailed documentation* covering quality assurance, testing, bias analysis and so on. High-level overview of these areas can be included on a model card where relevant, but any further detail should be accessible from the model card via links to full documentation.

[^1]: Model cards for model reporting https://arxiv.org/pdf/1810.03993

Having a template provides a clear first step for model developers to produce clear and open documentation. Standardisation can improve readability, allowing for valuable scrutiny of solutions both internally and publicly.

This template can be copied into a new or existing repository and populated with information about the models in use in a system/service/algorithm. Storing the model card in a repository alongside the code used to train, test and evaluate models will help to keep documentation up to date as both the model and it's documentation can be updated in parallel. If the code is published then the model card can be made public through the code publication process.


## Origins/Inspiration

Model cards were introduced in a [2019 paper](https://arxiv.org/pdf/1810.03993) and have been adapted by a number of organisations.

The initial design and set-up of the model card template drew inspiration from:
* [Google](https://modelcards.withgoogle.com/object-detection) 
* [Kaggle](https://www.kaggle.com/code/var0101/model-cards)
* [HuggingFace](https://huggingface.co/docs/hub/en/model-cards)

The use of model cards was recommended in the UK Government's [Generative AI Framework for HMG](https://www.gov.uk/government/publications/generative-ai-framework-for-hmg/generative-ai-framework-for-hmg-html#:~:text=a%20particular%20person.-,Ethics,-The%20ethical%20questions) (published Jan 2024). This specifically references Google's [2019 paper](https://arxiv.org/pdf/1810.03993) from which most inspiration was drawn.

## Content
The repo includes:

1. The model card template
    1. Specification
    2. Intended Use
    3. Data
    4. Methodology and Training
    5. Evaluation and Performance
2. An images folder where visualisations such as a confusion matrix can be stored for use in a model card

