# Detection of Fake News
![Fake_real-1_gebpwg](https://github.com/RayanZed/Detecting-Fake-News-With-Two-Classifiers-Using-Sci-Kit-Learn/assets/164723270/83f1119c-7f82-455a-83a2-58bbe4959384)

## Overview

### *This project utilizes advanced machine learning algorithms to effectively classify fake news articles by leveraging the powerful Sci-Kit libraries available in Python. By employing a combination of natural language processing techniques and sophisticated algorithms, we aim to develop a robust model capable of accurately distinguishing between genuine and fabricated news content.*

#### Dataset

The project utilizes the LIAR dataset as its primary data source, consisting of three files in .tsv format for test, train, and validation purposes. 
This dataset serves as a benchmark for fake news detection and is extensively described by William Yang Wang in the paper titled "Liar, Liar Pants on Fire": A New Benchmark Dataset for Fake News Detection, presented at the 55th Annual Meeting of the Association for Computational Linguistics (ACL 2017).

The original LIAR dataset contained 13 variables/columns across train, test, and validation sets, including the statement ID, label (with classes such as True, Mostly-true, Half-true, Barely-true, FALSE, Pants-fire), the statement itself, subject(s), speaker information, state details, party affiliation, credit history counts, and context.

For simplicity, this project initially focuses on two variables from the original dataset: the statement (news headline or text) and the label (True or False). These two classes were derived by consolidating the original six classes as follows:

* True (including True, Mostly-true, and Half-true from the original dataset)
  
* False (including Barely-true, False, and Pants-fire from the original dataset)
  
* This reduction in classes simplifies the classification task while retaining the essence of distinguishing between genuine and fake news content.

The datasets used in the project are provided in CSV format: train.csv and test.csv available within the repository.

#### Code

In this project, we employ three essential packages to facilitate our data analysis and machine learning tasks:

* Scikit-learn (sklearn): This powerful machine learning library in Python offers a wide range of algorithms and tools for tasks such as classification, regression, clustering, and dimensionality reduction. We leverage sklearn to implement various classifiers, perform model evaluation, and handle data preprocessing tasks efficiently.

* NumPy: NumPy is a fundamental package for scientific computing in Python, providing support for large, multi-dimensional arrays and matrices along with a collection of mathematical functions. We utilize NumPy extensively for data manipulation, numerical computations, and array operations, making our code more efficient and concise.

* SciPy: SciPy is another essential library built on top of NumPy, offering additional functionalities for scientific and technical computing tasks. It includes modules for optimization, integration, interpolation, linear algebra, and more. In our project, we leverage SciPy for advanced mathematical computations, statistical analysis, and optimization tasks that complement the capabilities of NumPy and scikit-learn.

#### Dependencies

* Python 3.x
  
* NumPy
  
* Scikit-learn

* SciPy
  
#### Usage

install the required dependencies:

pip install pandas scikit-learn

#### Contributing

Contributions to enhance this repository are welcome. Please feel free to open issues or submit pull requests.

#### License

This project is licensed under the MIT License.
