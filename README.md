# Restaurant Named Entity Recognition (NER) using spaCy

This repository contains code for training a Named Entity Recognition (NER) model for restaurant-related text using spaCy.

## Installation

1. Install spaCy and download the large English model:
   ``` python -m spacy download en_core_web_lg ```
3. Install the transformers component for spaCy:
   ``` pip install 'spacy[transformers]' ```

## Training

1. Go to [spaCy's training page](https://spacy.io/usage/training) to get the contents of the `base_config` file.

2. Save the contents of the `base_config` file under the same directory as your notebook.

3. Update the configurations in the generated `config.cfg` file as necessary, selecting NER, CPU/GPU, and accuracy for optimization.

4. Run the provided notebook file to start training the model.

## Dataset

The dataset used for training this model consists of restaurant-related text, which includes reviews, menus, and other restaurant-related content.

## Notebooks

- `notebook.ipynb`: Jupyter notebook containing code for training the NER model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


