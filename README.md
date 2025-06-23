# Amazon Groceries Recommendation System Using Association Rules

- Context: Personalized product recommendations enhance user experience, increase purchase likelihood, and drive revenue growth
- Scope: Identify co-occurrence of products and select best products based on the ratings of each category under consideration. 

## 📁 Dataset
- The data consists of Amazon Reviews data for Groceries and Gourmet Food Category covering records between 2019 and 2023 with total interaction 2,425,957
- Source: https://snap.stanford.edu/data/amazon/productGraph/

## 🧠 Models
![image](https://github.com/user-attachments/assets/7466080b-8952-4ea6-9961-2eddee20f126)

## 🔧 Preprocessing
- Exclude users with unusually high number of reviews
- Ensure there is at least 1 transaction in a list/category
- Extract the second layer from “category” to use for Association Rule
- Transform to market basket

## 📊 Evaluation Metrics
- **Lift**
- **Confidence**
- **Support**

## 🧪 Results
- The consequent categories with highest lifts are Snacks & Sweets, with repetitive items in the antecedents.
- All the consequents belong to two categories: Snacks & Sweets or Pantry Staples
![image](https://github.com/user-attachments/assets/2ba11a4e-036b-4cf5-aa16-54ea1decc29b)

![image](https://github.com/user-attachments/assets/4adda73a-c2fd-49fc-b77b-2e536802ee5a)

## 📌 Limitation & Future Improvement
- Threshold sensitivity: different threshold leads to different results
- Lack of basket data.
- Association rule is not suitable for large datasets.
- Incorporate price into the model.
- Consider improve the model when we have sparsity in rating.


## 📬 Contact
Feel free to reach out if you want to collaborate or ask questions!

