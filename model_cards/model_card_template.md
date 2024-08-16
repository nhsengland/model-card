# {Model Name} Model Card

## Specification

_This section contains top-level information about what the model is. The details of this section are in a table format so as to quickly give the reader the relevant information._

|  |  |
| ---- | ---- |
| **Description:** | _General overview of the model, what it does, and motivation for developing it. No more than one paragraph_|
| **Model Type:** | _Specify the type of model (e.g., clustering, time series, deep learning models, reinforcement learning, supervised learning, ensemble, hybrid, etc.) and describe its main characteristics_|
| **Developed By:** | _Name of the developer or development team_ |
| **Status** | _Development/Development complete/Production (live/in use)_|
| **Launch Date:** | _Expected or Launch Date_ |
| **Version** | _As in model registry_ |

## Intended Use

_This section goes into more detail about why the model was built and who it was for. This section can go into more depth than previous, but should still be as succinct as possible._

**Development Background:** _A brief description of the model's development purpose and context, this is a chance to expand on the description, any additional background information on the model's focus area, who this originally created for and how the model fits into the wider decision making process._

**Scope:** _Specific application or functionality of the model._

**Intended Users:** _Describe who the model is intended for._

**Use cases out of scope:** _Describe any potential use cases out of scope._

## Data

_This section should provide basic details about the data used in and by the model. Any more detail should be provided in supplementary information, such as a DataSheet._

**Data Overview:** _A brief overview of where the data comes from, the type of data and it's coverage etc._

**Sensitive Data:** _How is any sensitive data handled?_

**Pre-processing and cleaning:** _How was the data cleansed?, was it's suitability verified before use?, why these datasets?, are they representative?_

**Data Split:** 
| Type | Split | Description |
| ---- | ---- | ---- |
| **Training:** | x% | _Use this space to describe the training data, expanding on the data overview_ |
| **Testing:** | x% | _Use this space to describe the testing data, expanding on the data overview_ |
| **Validation:** | x% | _Use this space to describe the validation data, expanding on the data overview_ |

## Methodology and Training

_This section should explain how the model was built to do what it does, including any justification where required. Lengthy debate or detail of particular methodology should be provided in user documentation and not in the model card._

**Model Type:** _Specify the type of model (e.g., clustering, time series, deep learning models, reinforcement learning, supervised learning, ensemble, hybrid, etc.) and describe its main characteristics._

**Models Used:** _What models were used (e.g. embedding x + classifier y)_

**Justification:** _Explain here why this approach was taken over another._

**Feature Engineering:** _Details on the process of creating and selecting features if relevant._

**Algorithm Details:** _Describe the main steps in the model inference process, e.g. are there any pre or post processing steps or how is the model output interpreted or acted upon?_

**Alternative Methods Considered:**
1. _Option B_
2. _Option C etc._

### Training Methods:

**Training Process:** _Description of the model training process. Link to relevant code or repository used to create the model._

**Hyperparameter/Fine Tuning:** _Detail any additional  processes to select appropriate hyperparameters or other types of fine tuning._

## Evaluation and Performance

_This section details how well the model performs._

_Note: The metrics and visual in this section is an example only and is not intended to indicate the evaluation methods and visuals you should use. Please adjust the types of metrics and visuals appropriately to suit requirements._

### Model Evaluation

**Evaluation Process:** _How the model is evaluated._

**Evaluation Focus:** _If relevant, provide detail and an explanation for why a particular metric (e.g. F1 score), or performance for/across specific data subset/s was prioritised._

**Performance breakdown:** _Details on the model's performance across different subsets or categories of data._

**Metrics:** _Use the table below for performance metrics, adjust as appropriate._

| Metric | Value |
| ---- | ---- |
| F1 Score | 0.00 |
| Precision | 0.00 |
| Recall | 0.00 |

_The below confusion matrix is an example of how to include an image in this model card - visuals can be helpful but it is not a requirement to use a confusion matrix._

<img src="./visuals/example-cm.png" width="400"/><br>

**Performance in Deployment**: _Detail the performance of the model in deployment once monitoring is completed. State any considerations taken for the model inference time and provide the results in brief._

### Ethical Considerations

**Bias and fairness analysis:** _Describe the approach for analysing error and the insights gained from them._

**Implications for human safety:** _Potential impact on human life, potential harm and safety and mitigation._

### Caveats

**Caveats and Limitations:** _Describe here any important information or limitations (e.g.how will an NLP model handle changes in human language like new slang)._
