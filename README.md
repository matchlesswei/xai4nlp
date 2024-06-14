# xai4nlp

This GitHub repository contains Jupyter notebooks demonstrating the usage of SHAP (SHapley Additive exPlanations) and Captum to explain Transformer models for various NLP (Natural Language Processing) tasks. The notebooks cover tasks such as sentiment analysis, named entity recognition (NER), question answering, translation, and text generation. The explanations provided by SHAP and Captum help in understanding the inner workings and decision-making processes of Transformer models.

## Repositories Involved

This repository collects usages and examples from three open-source GitHub repositories:

1. [Captum](https://github.com/pytorch/captum): Captum is a model interpretability library developed by MetaAI for PyTorch models. It provides a wide range of interpretability algorithms, including SHAP, to explain the behavior of deep learning models.

2. [Transformers-Interpret](https://github.com/cdpierse/transformers-interpret): This repository is a wrapper that facilitates using Captum specifically for Transformer models. It builds upon Captum's functionality and provides a convenient interface for interpreting Transformer models in the context of NLP tasks.

3. [SHAP](https://github.com/slundberg/shap): SHAP is a general model-agnostic interpretability library. It offers a unified approach to interpret black-box models and provides explanations in terms of feature importance, helping to understand the model's decision-making process.

## Dependencies and Setup
To install the necessary dependencies, use the following command:

  ```bash
   pip install -r requirements.txt
   ```

Additionally, the project's dependencies are managed using [Python Poetry](https://python-poetry.org/), a package and dependency management tool. Poetry simplifies the installation and management of project dependencies.

To set up the project, follow these steps:

1. Ensure you have Python 3.10 installed on your system.

2. Install Poetry by following the official [Poetry installation instructions](https://python-poetry.org/docs/#installation).

3. Clone this GitHub repository to your local machine:

   ```bash
   git clone https://github.developer.allianz.io/wei-ding/xai4nlp.git
   ```

4. Navigate to the cloned repository:

   ```bash
   cd xai4nlp
   ```

5. Use Poetry to install the project dependencies:

   ```bash
   poetry install
   ```

   This command will create a virtual environment and install the required Python packages specified in the `pyproject.toml` file.

6. Activate the virtual environment:

   ```bash
   poetry shell
   ```

   Activating the virtual environment will ensure that the installed packages are isolated and won't interfere with other Python environments on your system.

7. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   The command will open Jupyter Notebook in your default web browser.

8. Update package version in toml and run:

   ```bash
   poetry update
   ```

   This command will update the packages installed in the virtualenv with new version defined in toml.
9. To leave the virtual environment:

   ```bash
   decative
   ```

   This command will leave in virtual environment in the terminal.

## Usage

The repository contains several Jupyter notebooks, each focusing on explaining a specific NLP task with one library. These notebooks demonstrate how to use SHAP and Captum for interpreting Transformer models.

To explore the notebooks, follow these steps:

1. Launch Jupyter Notebook by following the instructions provided in the "Dependencies and Setup" section.

2. In the Jupyter Notebook interface, navigate to the notebook you wish to explore.

3. Open the selected notebook and follow the instructions and code examples provided within.

   The notebooks contain detailed explanations, code snippets, and visualizations to guide you through the process of interpreting Transformer models using SHAP and Captum.
