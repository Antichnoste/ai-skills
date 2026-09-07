# Math to ML

## Purpose

Explain mathematical concepts through their practical role in machine learning.

The goal is not only to explain the mathematics itself, but to show why it matters for models, optimization, loss functions, data, and training.

## When to use

Use this skill when the user wants to understand a mathematical concept related to machine learning, including:

* linear algebra;
* probability;
* statistics;
* calculus;
* optimization;
* information theory;
* numerical methods.

Typical topics include:

* vectors and matrices;
* dot products;
* matrix multiplication;
* eigenvalues and eigenvectors;
* gradients;
* partial derivatives;
* Jacobians and Hessians;
* expectation and variance;
* covariance and correlation;
* probability distributions;
* maximum likelihood estimation;
* entropy and cross-entropy;
* convexity;
* regularization.

## Workflow

### 1. Start with the mathematical idea

Explain what the concept represents before introducing heavy notation.

Answer questions such as:

* What does this quantity describe?
* What should I imagine geometrically or probabilistically?
* Why was this concept introduced?

Use simple language first.

### 2. Introduce the formal definition

Write the mathematical definition and explain every important symbol.

Do not assume that notation is obvious.

If the formula contains several operations, explain them separately.

### 3. Work through a small numerical example

Use simple numbers that can be calculated manually.

Show intermediate steps when they help reveal the meaning of the concept.

Avoid examples that require unnecessary arithmetic.

### 4. Connect the mathematics to ML

Explain where this concept appears in machine learning.

For example, connect it to:

* model parameters;
* features;
* predictions;
* loss functions;
* gradients;
* optimization;
* probability models;
* neural network layers;
* training stability.

Prefer a concrete ML example over a generic statement.

### 5. Show what happens during model training

When applicable, explain how the mathematical concept affects the learning process.

Examples:

* how feature scale changes gradients;
* how eigenvalues affect optimization;
* how variance describes data spread;
* how derivatives determine parameter updates;
* how likelihood becomes a loss function;
* how matrix multiplication represents a neural network layer.

### 6. Explain the common confusion

Identify concepts that are easy to mix up.

Examples:

* variance vs standard deviation;
* correlation vs causation;
* probability vs likelihood;
* gradient vs derivative;
* eigenvector vs singular vector;
* standardization vs normalization;
* linear model vs linear relationship between features.

Explain exactly where the distinction appears.

## Rules

* Start with intuition before formalism whenever possible.
* Do not make the explanation unnecessarily academic.
* Never introduce formulas without explaining what they represent.
* Do not skip important intermediate mathematical steps.
* Prefer small numerical examples.
* Connect abstract mathematics to actual ML behavior.
* Clearly distinguish mathematical guarantees from intuition or approximation.
* When a concept has a geometric interpretation, explain it.
* When useful, show how changing one quantity affects model training.
* Avoid introducing advanced terminology unless it helps answer the question.
* Do not turn the explanation into a full textbook chapter unless requested.

## Preferred explanation structure

For most topics, use:

1. Intuition
2. Mathematical definition
3. Numerical example
4. Connection to ML
5. Effect on training
6. Common confusion

For simple questions, shorten the structure instead of mechanically including every section.

## Example

For a question such as:

> Why does feature scaling affect gradient descent?

A good explanation should connect:

$$
\frac{\partial L}{\partial w}
$$

to the scale of the corresponding feature, show a small numerical example, and then explain how different feature scales change the geometry of the loss surface and the learning rate required for stable optimization.

The explanation should not stop at saying that "gradient descent works better with normalized data."
