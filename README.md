# 🧠 Apriori - Machine Learning  

Let's say you want to improve your knowledge of **customer buying behavior** 🛒 —  
such as knowing their **next buying move** or **what other products they buy together**.  

Uncover new patterns across different aspects like **time, place, and branch** 🕓📍🏬.  
Therefore, marketers can leverage this information by:  
- launching **great-deal bundling products** on particular goods 🎁  
- setting **product displays** strategically to capture attention 👀  
- and sending **personalized notifications** that customers are likely to click 💌  

This makes customers feel **understood** and encourages them to buy **complementary goods without thinking twice!** 🛍️💨  

The **Apriori Algorithm**, an **unsupervised machine learning model**, helps bring this initiative to life! ⚙️🤖  

---

## 📊 Apriori Components

1. **🧺 Frequent Itemsets** — most items that appear together in the basket  
2. **🔗 Association Rules** — implication like *“if you buy goods A and B, what next item will you buy?”*  
3. **📐 Metrics:**  
   - **📈 Support** → proportion of a specific item that appears in total transactions  
   - **💡 Confidence** → measures how often item B is purchased when item A is purchased  
     *(proportion of support A ∪ B to support A)*  
   - **⚖️ Lift** → measures the **strength of relationship** between goods A and B  
     *(confidence of A→B divided by support of B)*  
     - Lift values range from **<1, =1, >1**, representing negative, neutral, or positive relationships  

---

## 🧾 About Dataset

**Grocery member transaction retail dataset** 🛒  
[click this dataset]('https://github.com/Elzfe09/Apriori-Machine-Learning/blob/main/Groceries_dataset.csv')
Contains the following fields:  
- 🧍‍♂️ **Member Number**  
- 📅 **Date**  
- 🛍️ **Item Description**

---

✨ *Apriori helps marketers uncover the hidden “shopping logic” behind every basket,  
turning data into smart marketing decisions!* ✨
