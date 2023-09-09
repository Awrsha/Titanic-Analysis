# Titanic Ship Analysis Project

This project aims to predict the survival of passengers aboard the Titanic ship using various machine learning algorithms. The dataset used for this analysis is the famous Titanic dataset, and we have implemented Support Vector Machines (SVM), Decision Trees, Random Forest, Gradient Boosting, and Neural Networks for this task.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Algorithms Used](#algorithms-used)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during its maiden voyage, the Titanic sank after colliding with an iceberg. This project uses machine learning to predict whether a passenger survived or not based on various features like age, gender, ticket class, and more.

## Dataset

- The dataset used in this project can be found at [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data).

## Algorithms Used

1. **Support Vector Machines (SVM):** SVM is a powerful classification algorithm that aims to find the best separating hyperplane between two classes.

2. **Decision Trees:** Decision trees are used for both classification and regression tasks. They create a tree-like model of decisions and their consequences.

3. **Random Forest:** Random Forest is an ensemble learning method that combines multiple decision trees to improve accuracy and reduce overfitting.

4. **Gradient Boosting:** Gradient Boosting is another ensemble learning technique that builds an additive model in a stage-wise manner, improving predictive accuracy.

5. **Neural Networks:** Neural Networks, specifically deep learning models, are used to build complex non-linear relationships between features and the target variable.

## Results

The best accuracy achieved among these algorithms was 87% using a Jupyter Notebook environment. The detailed results and analysis can be found in the project's Jupyter Notebook.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Awrsha/Titanic-Analysis.git
   cd titanic-ship-analysis
   ```

2. Install the required dependencies (see [Dependencies](#dependencies)).

3. Run the Jupyter Notebook to reproduce the analysis:

   ```bash
   jupyter notebook Titanic.ipynb
   ```

4. Follow the instructions in the notebook to execute the code and explore the results.

## Dependencies

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-Learn
- TensorFlow (for Neural Networks)
- Matplotlib
- Seaborn

You can install these dependencies using `pip` or `conda`. For example:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib seaborn
```

## Contributing

If you would like to contribute to this project, please open an issue or submit a pull request. We welcome contributions and suggestions!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
