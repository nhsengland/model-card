# Model Name Here Model Card

## Details
| Detail | Information |
| ---- | ---- |
| **Description:** | General Overview of the model, what it does, and motivation for developing it. No more than one paragraph|
| **Model Type:** | Specify the type of model (e.g., clustering, time series, deep learning models, reinforcement learning, supervised learning, ensemble, hybrid, etc.) and describe its main characteristics|
| **Developed By:** | Name of the developer or development team |
| **Launch Date:** | Expected or Launch Date |
| **Version** | As in model registry |

## Intended Use

**Development Background:** A brief description of the model's development purpose and context, this is a chance to expand on the description, any additional background information on the model's focus area, who was this created for and how the model fits into the wider decision making process.

**Scope:** Specific application or functionality of the model

**Intended Users:** Who is the model intended for?

**Use cases out of scope:** Describe any use cases out of scope

## Data

**Data Overview:** A brief overview of where the data comes from, the type of data and it's coverage etc.

**Sensitive Data:** How is any sensitive data handled?

**Pre-processing and cleaning:** How was the data cleansed?, was it's suitability verified before use?, why these datasets?, are they representative?

**Data Split:** 
| Type | Split | Description |
| ---- | ---- | ---- |
| **Training:** | x% | Use this space to describe the training data, expanding on the data overview |
| **Testing:** | x% | Use this space to describe the testing data, expanding on the data overview |
| **Validation:** | x% | Use this space to describe the validation data, expanding on the data overview |

## Methodology and Training

**Model Type:** Specify the type of model (e.g., clustering, time series, deep learning models, reinforcement learning, supervised learning, ensemble, hybrid, etc.) and describe its main characteristics

**Models Used:** What models were used (e.g. embedding x + classifier y)

**Justification:** Explain here why this approach was taken over another

**Algorithm Details:** Describe the main steps when data is sent to the model for inference, e.g. how is text data converted into a binary class?

**Feature Engineering:** Details on the process of creating and selecting features if relevant

**Alternative Methods Considered:**
1. Option B
2. Option C etc

### Training Methods:

**Training Process:** Description of the model training process

**Hyperparameter Tuning:** Or rename this section to 'Fine Tuning'. Remove if not relevant

## Evaluation and Performance

### Model Evaluation

**Evaluation Process:** How was the model evaluated

**Evaluation Focus:** Was a particular metric (e.g. F1 score) focussed on and why?

**Performance breakdown:** Details on the model's performance across different categories

**Metrics:** Use the table below for performance metrics, adjust as appropriate
| Metric | Value |
| ---- | ---- |
| F1 Score | 0.00 |
| Precision | 0.00 |
| Recall | 0.00 |

<img src="images/example-cm.png" width="400"/><br>

**Performance in Deployment**: Detail the perfomance of the model in deployment once monitoring is completed. State any considerations taken for the model inference time and provide the results in brief.

### Ethical Considerations

**Bias and fairness analysis:** Describe the approach for analysing error and the insights gained from them.

**Implications for human safety:** Potential impact on human life, potential harm and safety and mitigatation

### Caveats

**Caveats and Limitations:** Describe here any important information or limitations (e.g.how will an NLP model handle changes in human language like new slang)

**Addtional Notes:** Record anything else here