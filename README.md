# Emotion Classification in Text Using Machine Learning

## Overview
This repository contains a machine learning project aimed at classifying emotions expressed in text samples. The project utilizes natural language processing (NLP) techniques to preprocess the data, extract features, and train models that can accurately identify emotions such as joy, anger, and fear.

## Dataset
The dataset used for this project is `nlp_dataset.csv`, which includes various text samples along with their corresponding emotional labels. Each entry consists of a comment and the emotion it conveys.

### Sample Data
| Comment                                                                                                   | Emotion |
|-----------------------------------------------------------------------------------------------------------|---------|
| I seriously hate one subject to death but now I feel reluctant to drop it.                               | fear    |
| I feel so full of life I feel appalled.                                                                   | anger   |
| I finally fell asleep feeling angry, useless and still full of anxiety.                                   | anger   |
| I feel like I have regained another vital part of my life which is living.                               | joy     |

## Project Structure
- `nlp_dataset.csv`: The dataset containing text samples and their associated emotions.
- `NLP - Emotion Classification in Text.ipynb`: Jupyter Notebook containing the complete code for loading, preprocessing the data, feature extraction, model training, and evaluation.


## Installation
To run this project, you need to have Python installed on your machine. You can set up the environment by following these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/emotion-classification.git
   cd emotion-classification
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the `emotion_classification.ipynb` notebook in Jupyter Notebook or Jupyter Lab.
2. Run the cells sequentially to load the dataset, preprocess the text data, extract features, train the models (Naive Bayes and SVM), and evaluate their performance.
3. Review the model comparison results to see which model performs better in classifying emotions.

## Results
The models are evaluated based on accuracy and F1 score:
- **Naive Bayes**: Accuracy: 0.91, F1 Score: 0.91
- **Support Vector Machine (SVM)**: Accuracy: 0.95, F1 Score: 0.95

The SVM model demonstrates superior performance in classifying emotions compared to Naive Bayes.

## Contributing
Contributions are welcome! If you have suggestions for improvements or additional features, please create a pull request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thank you to NLTK for providing tools for natural language processing.
- Special thanks to the contributors who helped improve this project.

---

Feel free to customize any sections according to your specific needs or preferences!

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/34812455/d588a0c2-9a10-4021-9bbf-38f59132a664/nlp_dataset.csv
