# **Hotel Booking Demand Analysis & Prediction**

## 📌 Project Overview
This project explores **hotel booking demand patterns** using **exploratory data analysis (EDA) and predictive modeling**. The dataset includes detailed booking information from **City and Resort hotels**, covering **booking trends, cancellations, customer demographics, and accommodation preferences**.

Through **Python-based data analysis**, we uncover key insights that help hotels **optimize revenue, improve customer experience, and reduce cancellations**. Finally, we develop a **predictive model** to determine whether a booking is likely to be canceled.

---

## 🎯 Key Questions & Insights
We set out to answer several important questions about hotel booking patterns:

✅ **How many bookings were canceled?**  
→ Nearly **35% of bookings were canceled**, impacting hotel revenue significantly.  

✅ **What is the booking ratio between Resort and City hotels?**  
→ **City hotels account for over 60%** of total bookings.  

✅ **Which year had the highest bookings?**  
→ **2016 saw a surge in bookings**, more than doubling compared to 2015, though demand slightly dropped in 2017.  

✅ **Which months are the busiest for hotels?**  
→ **July and August** experience peak bookings, while the start and end of the year see the least demand.  

✅ **Where do most guests come from?**  
→ **Portugal, the UK, France, Spain, and Germany** make up **80% of total bookings**.  

✅ **How long do people typically stay?**  
→ **City hotel guests** mostly stay for **1, 2, or 7 days**, while **Resort hotel guests** prefer **2-4 day stays**.  

✅ **Which accommodation type is most popular?**  
→ **Couple bookings (2 adults) dominate**, suggesting hotels should tailor packages and amenities accordingly.  

---

## 🧑‍💻 Predictive Modeling: Will a Booking Be Canceled?
To help hotels minimize cancellations, we built a **machine learning model** that predicts whether a booking will be **canceled** based on key features like:

📌 **Lead time, previous cancellations, deposit type, customer type, and special requests**  

### 📊 Steps Taken for Model Development:
🔹 **Feature Engineering** → Created new variables from existing data for better predictions  
🔹 **Data Preprocessing** → Cleaned and transformed categorical data into numerical values  
🔹 **Train-Test Split** → Divided data for model training and validation  
🔹 **Model Selection & Training** → Applied **classification models** to predict cancellations  
🔹 **Evaluation** → Assessed model accuracy and impact on business decisions  

---

## 📂 Dataset Information
📌 The dataset contains **hotel booking records**, including:

🔹 **Hotel type** (City vs. Resort)  
🔹 **Booking status** (Canceled or Not Canceled)  
🔹 **Arrival date & length of stay**  
🔹 **Number of adults, children, and babies**  
🔹 **Guest country of origin**  
🔹 **Distribution channels & market segments**  
🔹 **Customer type & special requests**  
🔹 **Room type (reserved vs. assigned)**  
🔹 **Lead time & previous booking history**  
🔹 **Car parking & special requests count**  

---

## 🛠️ Tools & Libraries Used
The project was implemented using **Python 3** with the following libraries:

- **Pandas** → Data manipulation & analysis  
- **Matplotlib & Seaborn** → Data visualization  
- **Scikit-learn** → Machine learning models  
- **PyCountry** → Country data mapping for guest origin analysis  

---

## 📂 Project Files
🔹 **`Hotel_Booking.ipynb`** → Jupyter Notebook with full **code, visualizations, and model development**  
🔹 **`hotel_bookings.csv`** → Cleaned dataset for analysis  

---

## 🌍 Data Source & Acknowledgments
📌 This dataset was originally published in the **Hotel Booking Demand Datasets** article by **Nuno Antonio, Ana Almeida, and Luis Nunes** in **Data in Brief, Volume 22, February 2019**.  

📌 **Thomas Mock & Antoine Bichat** cleaned and formatted the data for **TidyTuesday (Feb 11, 2020)**.  

📌 The dataset was made available by **Jesse Mostipak** on **Kaggle**:  
🔗 **[Download Here](https://www.kaggle.com/jessemostipak/hotel-booking-demand)**  

---

## 🚀 Key Takeaways & Business Impact
💡 **High cancellation rates** → Hotels need better **prepayment policies** to secure bookings.  
💡 **Peak season demand** → **July-August pricing strategies** should optimize revenue.  
💡 **Majority international guests** → **Country-specific marketing** can improve bookings.  
💡 **Couple-dominated bookings** → Hotels should **tailor amenities for two-person stays**.  

This analysis provides **data-driven insights** that can help hotels **maximize occupancy, reduce cancellations, and optimize customer engagement strategies**.

