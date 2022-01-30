# Books Rating Prediction Model
Given set of categorical and numerical characteristics of a book, the program predicts the expected rating the book would receive.

### Model and training characteristics
- Architecture: fully dense 5-layer neural network
- Optimizer: Stochastic Gradient Descent (SGD)
- Activation function: Rectified Linear Unit (ReLU)
- Loss measure:  Mean-square error (MSE)
- Split ratio: 4:1 train to test set, 4:1 validation train & test
- Qualitative transforms: one-hot encoding
- Quantitative transforms: standard scaling

### Future improvements
- PCA/dimensionality reduction techniques qualitative features
- NLP inclusion for further feature engineering on book titles (sentiment, embeddings, topic classification)
- More comparisons with other supervised models

### Installation:
1) Clone repository: `git clone https://github.com/importJL/Books-Prediction/`
2) Setup virtual environment: `python -m venv {environment name}`
3) Install requirements: `pip install -r requirements.txt`
4) Run notebook - `Books_Predict.ipynb`
