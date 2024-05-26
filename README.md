# Sentiment analysis Indonesian Marketplace Product Reviews - NLP 

## Datasets
[Indonesian Marketplace Product Reviews](https://www.kaggle.com/datasets/taqiyyaghazi/indonesian-marketplace-product-reviews/data)

## Notebook
https://www.kaggle.com/code/heykam/sentiment-analysis-product-reviews

## Model Selection
- 90.87% - BernoulliNB
- 92.31% - ComplementNB
- 92.79% - MultinomialNB
- 73.08% - KNeighborsClassifier
- 75.48% - DecisionTreeClassifier
- 90.38% - RandomForestClassifier
- 91.83% - LogisticRegression
- 93.27% - MLPClassifier
- 86.06% - AdaBoostClassifier

Model terbaik adalah MLPClassifier dengan akurasi 93.27%

## Output
Review: 'Pengiriman sangat cepat dan tepat waktu.' -> Sentimen: Positif
Review: 'Produk ini sangat buruk dan mengecewakan.' -> Sentimen: Negatif
Review: 'Produknya sangat bagus dan kualitasnya pun sesuai harga.' -> Sentimen: Positif
Review: 'Harga terlalu mahal dengan barang yang jelek.' -> Sentimen: Negatif
