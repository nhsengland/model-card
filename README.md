# NHS England Template Model Card

## What are model cards?

The main purpose of a model card is to display the essential components of models in a structured way.

Model cards are intended to be *short* documents that contain non-technical and technical content for a variety of audiences. They should be succinct, well-structured and easily digestible by the reader.

Model cards are one approach to increasing transparency between developers, users and stakeholders about details such as any data used, chosen methodology and performance. They are an example of a transparency tool which aims to standardise ethical practice and reporting[^1].

A model card is *not a replacement for detailed documentation* covering quality assurance, testing, bias analysis and so on. High-level overview of these areas can be included on a model card where relevant, but any further detail should be accessible from the model card via links to full documentation.

## When to use this template

This template can be used at any point during the model development lifecyle. It is recommended to start using and populating a model card as soon as model development begins because it serves as a useful piece of internal documentation.

Once a model is finalised, ready for deployment or put into production, a fully completed model card should be made available alongside the code used for model training.

To achieve full transparency, the code and model card should be published.

## How to use this template

Having a template is a helpful starting place for those who may not be familiar with model cards, and provides *an indication rather than a specification* of what information model developers should consider providing. The specific content and structure *should be flexed* to accommodate specific use cases and models, with the above purpose in mind.

This template can be copied into a new or existing repository and populated with information about the models in use in a system/service/algorithm. Storing the model card in a repository alongside the code used to train, test and evaluate models will help to keep documentation up to date as both the model and it's documentation can be updated in parallel. If the code is published then the model card can be made public through the code publication process.

### [Go to the template](model_cards/model_card_template.md)

## Inspiration

Model cards were first explored in a Google research paper[^1] in 2018 and are now widely used.

The initial design and set-up of this model card template took inspiration from:

* [Google](https://modelcards.withgoogle.com/object-detection)
* [Kaggle](https://www.kaggle.com/code/var0101/model-cards)
* [HuggingFace](https://huggingface.co/docs/hub/en/model-cards)

The use of model cards was recommended in the UK Government's Generative AI Framework for HMG[^2], published in January 2024. This specifically references the Google paper[^1] from which most inspiration was drawn.

## Content

This template repository includes:

1. [The model card template](model_cards/model_card_template.md)
    1. Specification
    2. Intended Use
    3. Data
    4. Methodology and Training
    5. Evaluation and Performance
2. Visuals folder to store visualisations (such as a confusion matrix) for use in a model card

[^1]: [Model cards for model reporting](https://arxiv.org/pdf/1810.03993)
[^2]: [Generative AI Framework for HMG](https://www.gov.uk/government/publications/generative-ai-framework-for-hmg)
