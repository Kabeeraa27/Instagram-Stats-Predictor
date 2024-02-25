# Instagram Statistics Prediction with Image Captioning

This project aims to predict Instagram statistics such as likes, shares, and saves based on generated captions using the Transformer library from Hugging Face. The project involves three main steps: 

1. **Image Caption Generation**: We start by importing an image from a dataset and generating a caption using the Transformer library from Hugging Face.

2. **Instagram Statistics Prediction**: After obtaining the caption, we import another dataset containing Instagram statistics such as likes, saves, comments, and captions. We use this dataset to predict the likes, shares, and saves based on the generated caption from the first dataset. For prediction, we utilize linear regression modeling.

3. **Integration and Final Prediction**: Finally, we integrate all these predicted values to predict the final statistics of a random image imported.

## Libraries Used

The following libraries were used in this project:
- `warnings`: For handling warnings
- `logging`: For logging messages
- `transformers.pipeline`: For generating image captions using pre-trained models
- `numpy`: For numerical computations
- `pandas`: For data manipulation and analysis
- `IPython.display.Image`: For displaying images in Jupyter notebooks
- `sklearn.linear_model.LinearRegression`: For linear regression modeling
- `sklearn.model_selection.train_test_split`: For splitting data into training and testing sets
- `sklearn.metrics.mean_squared_error`: For evaluating model performance
- `sklearn.feature_extraction.text.TfidfVectorizer`: For converting text data into numerical features

## Installation

To run this project, you need to install the following dependencies:

```bash
pip install transformers numpy pandas scikit-learn
```

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/instagram-stats-prediction.git
   cd instagram-stats-prediction
   ```

2. Run the Jupyter notebook `instagram_stats_prediction.ipynb` to execute the project.

3. Follow the instructions provided in the notebook to execute each step of the project.

## Contributors

- KABEER
- JAY

## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

