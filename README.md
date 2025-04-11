# Fit-Or-Fraud
# 💳 Fit or Fraud? – Credit Card Fraud Detection

Logistic Regression ile dolandırıcılık tespiti yapmaya yönelik bir mini makine öğrenimi projesi.

## 🚀 Hedef
Gerçek bir kredi kartı işlem verisi üzerinde sınıflandırma modeli kurarak, fraud (sahtekarlık) içeren işlemleri tespit etmeye çalışmak. 

## 🔍 Kullanılan Yöntemler
- Logistic Regression
- Cost Function & Gradient Descent
- Precision / Recall / F1 Score / ROC Curve
- Class Imbalance problemi ve çözüm yolları

## 📊 Dataset
- Kaynak: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 işlem → sadece 492'si fraud (%0.17)

## 📁 Dosya Yapısı
- `notebooks/`: Projenin ana notebook'u
- `data/`: Veri dosyası
- `requirements.txt`: Ortam kurulumu

## 🧠 Öğrendiklerim
- Dengesiz veri setlerinde neden `Accuracy` yeterli değildir
- Logistic Regression'da karar sınırları nasıl belirlenir
- Precision/Recall/F1 kullanarak model performansı nasıl optimize edilir

## 📷 Örnek Çıktılar
- Confusion Matrix
- ROC Curve
- Feature Importances (optional)

## 🔧 Kurulum
```bash
git clone https://github.com/kullaniciadi/fit-or-fraud.git
cd fit-or-fraud
pip install -r requirements.txt
