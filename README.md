# Robotics and ML-Tutor-LLM

Robotics and ML-Tutor-LLM is an educational AI chatbot designed to explain machine learning and robotics concepts using simplified language,
step-by-step reasoning, and worked examples.

The model is optimized for accessibility rather than purely technical precision, making it useful for beginners and intermediate learners studying topics such as gradient descent, transformers, overfitting, and backpropagation.

The model was trained on a custom educational dataset consisting
of approximately 100 manually curated machine learning and robotics
question-answer pairs. The dataset was manually assembled and refined using AI-assisted
generation workflows to create educational machine learning and
robotics explanations in an instruction-response format.

The dataset emphasized:
- simplified explanations,
- step-by-step reasoning,
- beginner accessibility,
- and example-driven teaching.

![Demo](demo.png)


## Features

- Step-by-step ML explanations
- Beginner-friendly responses
- Example-driven teaching style
- Lightweight conversational interface
- Failure-aware response analysis
- Transformer-based architecture

## Example Interaction

### User
> What is linear regression in ML?

### Model

> Simple Explanation

>Linear Regression
>Simple Linear Model
>
>Step-by-Step:
>
>1.Calculate slope (w)
>
>2.Calculate intercept(b)
>
>Example: y = w*x + b
>
>Key Idea: Straight Line
>
>Summary:
>
>  - Easy to understand
>  - Predicts well for simple data patterns
>
>Limitations:
>
>  - Not suitable for complex datasets


### User
> What is classification in ML?

### Model

>Example
>
>Classification
>Categorizing Data
>
>Examples:
>• Cats vs Dogs
>• Disease Types
>
>Goal: Assign Labels
>
>Steps:
>
>    Train model on examples
>    Make predictions
>
>Key Idea: Categories
>
>Example:
>
>    Classify images as cats or dogs.
>
>Benefits:
>
>    Understandable output
>
>Drawbacks:
>
>    Harder than prediction

