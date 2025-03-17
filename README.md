# data-tips
A data analysis performed on food servers' tips in restaurants

## **Data Understanding using Tips Dataset**

This notebook serves as a tutorial to help understand and analyze the **Tips** dataset, which records food servers' tips in restaurants. The dataset contains 244 records, described by 7 variables. The goal is to explore and analyze the factors influencing tips in the restaurant industry and use these insights for decision-making related to table assignments for servers.

---

### **Sections:**
1. **Data and Objective Understanding**
   - In this section, we load and explore the dataset to understand its structure, variables, and purpose. We will also define the problem we aim to solve using the data.
   
2. **Descriptive Statistics and Visualization Tools**
   - Here, we will calculate basic statistics (mean, median, standard deviation, etc.) and create visualizations (such as histograms, boxplots, and scatter plots) to gain insights into the distribution and relationships between the features.
   
3. **Your First Model: Regression**
   - In this section, we will implement a regression model to predict the amount of tip based on other variables such as total bill, day of the week, and party size. This section introduces the concept of regression and how to build a predictive model using Python.

4. **Some More Analysis**
   - This section will involve further analysis, to be prepared in collaboration with your mini-group partner. You will explore additional factors and build on the regression model, refining your understanding of which variables most affect the tips and how we can optimize the seating arrangements in the restaurant.

---

### **Dataset Description:**

The **Tips dataset** consists of the following variables:
- **Total Bill**: The total amount of the restaurant bill (numeric).
- **Tip**: The tip given by the customer (numeric).
- **Sex**: The gender of the customer (categorical: Male or Female).
- **Smoker**: Whether the customer is in the smoking section (categorical: Yes or No).
- **Day**: The day of the week the service was provided (categorical: Thurs, Fri, Sat, Sun).
- **Time**: The time of day (categorical: Lunch or Dinner).
- **Size**: The number of people in the party (numeric).

---

### **Objective:**
Restaurant managers want to know which factors most influence the amount of the tip given to servers. By understanding these factors, managers can improve table assignments, avoid unfair treatment, and optimize their seating arrangements.
