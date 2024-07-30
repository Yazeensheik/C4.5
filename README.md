# C4.5
C4.5: A decision tree algorithm for classification tasks
# C4.5 Decision Tree and Playtennis Dataset

This repository contains an implementation of the C4.5 decision tree algorithm and a sample dataset `Playtennis.csv` for demonstration purposes.

## Files in the Repository

- **C4.5.ipynb**: A Jupyter notebook implementing the C4.5 decision tree algorithm.
- **Playtennis.csv**: A sample dataset used to demonstrate the C4.5 algorithm.
- **CART.ipynb**: A Jupyter notebook implementing the CART decision tree algorithm for comparison.

## C4.5 Decision Tree Algorithm

The C4.5 algorithm is an extension of the ID3 algorithm and is used for classification tasks. It builds a decision tree based on the concept of information entropy and is able to handle both continuous and categorical data.

### Features of C4.5

- Handles both categorical and continuous features.
- Deals with missing values.
- Prunes trees after creation to remove branches that do not provide additional information.

## Playtennis Dataset

The `Playtennis.csv` dataset is a simple dataset that records weather conditions and whether or not a game of tennis was played. It has the following columns:

- **Outlook**: The weather outlook (Sunny, Overcast, Rain).
- **Temperature**: The temperature (Hot, Mild, Cool).
- **Humidity**: The humidity (High, Normal).
- **Wind**: Whether it is windy (Weak, Strong).
- **PlayTennis**: The target variable indicating whether tennis was played (Yes, No).

## Usage

1. Clone the repository to your local machine.
    ```sh
    git clone https://github.com/your-username/C4.5-Playtennis.git
    ```

2. Open the `C4.5.ipynb` notebook in Jupyter Notebook or JupyterLab to explore the implementation of the C4.5 algorithm.
3. Open the `CART.ipynb` notebook to explore the implementation of the CART algorithm.
4. Use the `Playtennis.csv` dataset within the notebooks or in your own analysis.

## Getting Started

To run the notebooks, you will need to have Python and Jupyter Notebook installed. You can install the required packages using the following commands:

```sh
pip install jupyter
pip install pandas
pip install numpy
pip install scikit-learn
