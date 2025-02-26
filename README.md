# Explainable-AI

- The need for Explainable AI keeps growing as the adoption of AI grows. This is majorly due to the fact that Models growth in complexity the outputs can not be justified.

- The code samples(from a Colab example) serve to unbox the so-called black-box ML models.

- Areas of growing adoption of AI: Banking, Internet of Things(IoT), retail, financial services, healthcare, manufacturing

## Why the urgent need for Explainable AI (xAI)?

The need for less uncertainty and more transparency in predictions and the need to explain the relationship between the input and the output

1. If an AI model rejects a user credit card, applicants should know why the application denied and steps to improve outcome
2. If an AI model predicts likelihood of someone developing diabetes- should also provide reasons why
3. Self driving cars should recognize obstacles on the road the rationale behind them

Consequentlly AI models have been seen as mysterious blackboxes

## Explainability vs Interpretability

**Explainability** : Model's ability to give rationale/reason behind prediction and the degree to which they can be relied upon

Reasons why explainability is ideal: 

1. Models need to be interpretable without bias- decisions can be made naturally without bias
2. Forecasts maybe more transparent: Distinguishing between false and true causality
3. Models must be explained without compromising/sacrificing the quality of learning experiences/iterations

### The mission of XAI: 
**Reliability**: Model prediction's confidence, stability, resilience are critical aspects of model reliability


- **Model-specific** : These explanations may be derived from a certain kind of model.
- **Model agnostic**: The XAI uses the ML model as a "black box" without assuming any
knowledge of the internals to give explanations under an agnostic approach.

- **Associations**: Machine learning and deep learning models use associations to understand
how to generate predictions. We may make correlations between two variables. There are
correlations in the model that cannot be explained, which are false correlations. So, it's
critical to record genuine Correlation.

- **Local interpretation**: Local interpretation gives a notion of interpreting a single data point.
Why does the model forecast that a borrower would default? This is a local interpretation.
Sub-local interpretation: A sub-local interpretation does so for a small subset of data points
rather than explaining them.

- **Textual explanations**: Text-based explanations use both quantitative and linguistic
components to convey the significance of specific model parameters.

- **Trust**: Data quality, true causability, and algorithm choice all play a role in determining the

