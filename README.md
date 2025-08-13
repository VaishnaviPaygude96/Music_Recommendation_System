# 🎵 Music Recommendation System

A Python-based **music recommender system** that suggests similar songs based on their metadata using **content-based filtering** and **cosine similarity**.

## 📌 Features
- Recommends songs similar to a given track
- Uses **pandas**, **numpy**, and **scikit-learn** for data handling and similarity calculations
- Works with music datasets (e.g., Spotify)
- Simple and easy-to-use interface

## 🛠️ Technologies Used
- **Python 3.x**
- **pandas** – Data manipulation
- **numpy** – Numerical operations
- **scikit-learn** – Feature vectorization & similarity computation
- **Jupyter Notebook** – Development & testing

## 📂 Project Structure
```
Music_Recommendation_System/
│── dataset/                # CSV files containing song data
│── Music_Recommendation.ipynb  # Main Jupyter Notebook
│── requirements.txt        # Python dependencies
│── README.md               # Project documentation
```

## 📊 How It Works
1. **Load Dataset** – Import music data from CSV  
2. **Preprocess Data** – Handle missing values, select relevant features  
3. **Feature Extraction** – Combine metadata like artist, genre, and lyrics (if available)  
4. **Vectorization** – Convert text features into numerical form using TF-IDF  
5. **Similarity Calculation** – Use **cosine similarity** to find similar tracks  
6. **Recommendation** – Display top N similar songs  

## 🚀 Installation & Usage
```bash
# Clone this repository
git clone https://github.com/VaishnaviPaygude96/Music_Recommendation_System.git

# Navigate into the folder
cd Music_Recommendation_System

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook
```

Open `Music_Recommendation.ipynb` and run the cells to test recommendations.

## 📌 Example Output
**Input:** "Shape of You"  
**Output Recommendations:**
1. Galway Girl  
2. Perfect  
3. Thinking Out Loud  
4. Photograph  
5. Happier  

## 📜 License
This project is licensed under the **MIT License** – you are free to use, modify, and distribute it.
