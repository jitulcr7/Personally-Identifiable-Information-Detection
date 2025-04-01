# Personally-Identifiable-Information-Detection
![Image](https://github.com/user-attachments/assets/8680a1f3-5b7e-4cf5-91ed-02293840f804)

# Project Aim
The PII Data Detection project is centred on the creation of a feature that analyses and categorizes Personally Identifiable Information and removes it from unstructured text. This project shall apply both machine learning (ML) and natural language processing (NLP) to improve the data protection framework, conform to regulatory principles, and strengthen the protection of individuals’ rights. The identification and containment of PII are something that should be encouraged to prevent identity thefts, fraud, as well as other unlawful acts that come with it. To add, by putting measures such as proper PII detection, organizations remain protected and so does customers’ sensitive information, therefore leading to reputation enhancement in the ever-advancing digital economy.

# Objective
The use case of the Personally Identifiable Information (PII) Data Detection project is the creation of a sophisticated feature that can recognize, classify, and mask PII in raw text with ML and NLP. This project solves the challenge of ensuring that organisations respect individuals’ privacy and meet the global and regional high standards on data protection.
The detailed objectives of the project include:

    ●	To design an efficient PII detection algorithm that can accurately identify various forms of PII within unstructured text.
    ●	To categorize identified PII into direct identifiers and quasi-identifiers to tailor redaction strategies appropriately.
    ●	To implementing a robust redaction mechanism to effectively mask sensitive information while preserving data utility.
    ●	To evaluate the performance of the developed feature in different scenarios and refine the model to improve accuracy and reliability.
    ●	To ensure the solution integrates seamlessly with existing data processing workflows.

# Risk Assessment and Mitigation Strategies
![image](https://github.com/user-attachments/assets/dca1566c-4562-4853-9183-ff84e160aa11)
Redaction and identification of Personally Identifiable Information (PII) are essential when processing sensitive data in order to protect privacy and guarantee adherence to laws such as the GDPR. If disclosed, personally identifiable information (PII) such as names, email addresses, phone numbers, addresses, job titles, and more may result in identity theft, financial fraud, or privacy issues.

# Technical Stack

**Python:** Used for its rich libraries in machine learning and natural language processing (NLP).

**NLP Techniques:** Tokenization, stemming, lemmatization, and stopword removal to preprocess and clean text for PII detection.

**TF-IDF:** Converted text to numerical features, emphasizing important terms for PII like names and emails.

**Machine Learning Models:** Logistic Regression for multi-label classification; Random Forest performed best due to its robustness in handling noisy data.

**SMOTE:** Addressed class imbalance by generating synthetic data for underrepresented PII categories.

**Cross-Validation:** Ensured model robustness and prevented overfitting through k-fold cross-validation.

# NLP Techniques Impact:

**Tokenization:** Helped split the text into manageable units (tokens). This allowed the models to analyze each word individually, which improved precision in detecting specific PII categories (e.g., names, emails).

**Stemming and Lemmatization:** Reduced words to their base forms, helping the models recognize variations of the same word (e.g., "address" vs. "addresses"). This improved the recall of certain PII types.

**Stopword Removal:** By removing irrelevant words like “the” or “is,” the models focused on more meaningful terms, which enhanced precision, especially in detecting identifiers like names and job titles.

**TF-IDF (Term Frequency-Inverse Document Frequency):** Provided a numerical representation of the text based on word importance. This significantly improved model performance by helping the models prioritize important PII-related terms and ignore less relevant words.

# Conclusion 

**Key Achievements:**
Successfully developed and implemented a PII detection and redaction feature using machine learning and natural language processing (NLP) techniques.
The Random Forest model emerged as the best performer in detecting multiple PII categories from unstructured text due to its ability to handle noisy and complex data.

**Challenges Faced:**
Data Imbalance: Class imbalance was a significant challenge, with some PII categories being underrepresented. This was addressed using the SMOTE technique, which improved recall for minority classes like phone numbers.
Noisy Data: Handling noisy and unstructured text was difficult, particularly for models like SVM and Logistic Regression, which struggled with ambiguous data.

**Model Performance:**
Random Forest outperformed other models due to its flexibility and robustness in managing multi-label classification for diverse PII categories.
Logistic Regression and SVM were effective in linear cases but less capable of dealing with noisy, complex data.








