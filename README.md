# 🍊 Citrus Leaf Disease Detection


## Models compared
| Model | Accuracy | Precision | Recall | F1 |
|---|---|---|---|---|
| CNN | [98.1 ]% | [96.2 ] | [97.1] | [97.0] |
| SVM | [95.8]% | [95.9 ] | [95.8] | [95.8] |
| Random Forest | [95.8]% | [95.9] | [95.8] | [95.8] |
| KNN | [94.4]% | [94.5] | [94.4] | [94.4] |

**Best model:** [CNN] with [98.1]% accuracy.

## Workflow
1. Dataset collection and cleaning
2. Preprocessing and augmentation
3. Model training in Google Colab
4. Evaluation and comparison
5. Deployment with Streamlit

## Tech stack
Python, TensorFlow/Keras, scikit-learn, NumPy, Streamlit

## Project structure
- `CitrusDisease.ipynb`: training and evaluation notebook
- `app.py`: Streamlit app
- `models/`: trained models
- `requirements.txt`: dependencies

```bash
git clone https://github.com/Genie4pe/newcitrus
cd newcitrus
pip install -r requirements.txt
streamlit run app.py
```

## Author
John Momodu · https://www.linkedin.com/in/john-momodu-330b5b339
