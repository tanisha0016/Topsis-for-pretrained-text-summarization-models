
# TOPSIS for Selecting the Best Pre-Trained Text Summarization Model  

This project applies the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method to rank **pre-trained text summarization models** based on multiple evaluation criteria.  

## 🚀 Features  
- **Evaluates models** based on ROUGE scores, inference time, and model size.  
- **Ranks models** using the TOPSIS technique.  
- **Visualizes results** with bar charts and tables.  

## 📌 Requirements  
Install the necessary Python libraries using:  
```bash
pip install numpy pandas matplotlib topsis-python
```

## 📂 Dataset
The dataset contains various summarization models with:
ROUGE-1
ROUGE-2
ROUGE-L scores
Inference time (Lower is better)
Model size (Lower is better)


## 📜 Usage
Run the following command to apply TOPSIS and generate rankings:

```bash
python topsis_summarization.py
```

## 📊 Results
The script outputs a ranked CSV file and a bar chart showing the best model.

## 📄 License
This project is open-source and available under the MIT License.
