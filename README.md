# In22Labs

#Course Recommender using EDX and Coursera Datasets Combined 

This is a course recommendation system that suggests relevant online courses based on user interests, skills, and the desired difficulty level. The system uses natural language processing techniques to analyze course descriptions and recommend the most suitable courses.

## Features

- Preprocesses course descriptions by removing punctuation, converting to lowercase, and removing extra whitespace.
- Extracts features from course descriptions using TF-IDF vectorization.
- Calculates similarity scores between user interests and course descriptions.
- Filters courses based on similarity scores and the required difficulty level.
- Provides top recommendations based on difficulty level and similarity scores.
- Suggests additional courses based on user skills.

## Requirements

- Python 3.x
- pandas
- scikit-learn

## Usage

1. Clone the repository or download the code.
2. Ensure that the dataset file `combined_dataset.csv` is present in the same directory.
3. Install the required dependencies.
4. Run the `In22labs_ps2.ipynb` file stpe by step.
5. Follow the code to provide user inputs such as interests, skills, and difficulty level at the last code snippet.
6. Receive course recommendations based on the provided inputs.

## Dataset

The course information used in this recommendation system is obtained from the following Platforms:

- [edX](https://www.edx.org)
- [Coursera](https://www.coursera.org)

A special thanks to these platforms, which enables the development of this recommendation system.

## Credits

- The code in this repository was developed by Deep Patel.
- The course recommendation algorithm is based on techniques from the field of natural language processing and information retrieval.
