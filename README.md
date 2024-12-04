# housing-price-prediction-dl
A deep learning project focused on solving a regression task to predict housing prices using real-world data. This project leverages neural networks to model complex relationships in the data and provide accurate predictions.

---

# **Housing Price Prediction with Deep Learning**

## **Overview**
This project demonstrates the application of **deep learning techniques** to predict housing prices. Using a fully connected neural network (Multi-Layer Perceptron - MLP), the model effectively handles the regression task by capturing intricate patterns and relationships in the dataset. This project showcases the complete workflow, from data preprocessing to model evaluation.

----------------

## **Features**
- **Data Preprocessing**:  
  - Addressed missing values and identified outliers for robust analysis.  
  - Applied feature scaling and normalization to prepare the data for model training.  

- **Neural Network Architecture**:  
  - Designed an MLP optimized for regression tasks.  
  - Experimented with hyperparameter tuning to enhance performance (e.g., layer count, activation functions, learning rate).  

- **Model Evaluation**:  
  - Assessed model accuracy using metrics such as **Mean Absolute Error (MAE)** and **Mean Squared Error (MSE)**.  

- **Visualization**:  
  - Generated detailed loss curves to monitor training progress.  
  - Plotted **actual vs predicted prices** for better insight into model performance.

--------

## **Technologies Used**
- **Python**  
- **TensorFlow**  
- **Keras**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**

---

## **How to Use**

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/GovindaTak/housing-price-prediction-dl.git
   ```

2. **Navigate to the project directory**:  
   ```bash
   cd housing-price-prediction-dl
   ```

3. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**:  
   ```bash
   jupyter notebook Housing_Price_Prediction.ipynb
   ```

---

## **Results and Insights**
- The **neural network model** successfully achieved **low MSE and MAE**, indicating accurate predictions for housing prices.  
- The visualization of **actual vs predicted prices** reflected the model's capability to capture real-world trends.  
- The training loss curves highlighted smooth and consistent convergence, showcasing the effectiveness of the chosen architecture and hyperparameters.

---

## **Project Structure**
- **Dataset**: Includes the preprocessed and cleaned housing dataset.  
- **Notebook**: Step-by-step implementation of the neural network and analysis.  
- **Results**: Contains evaluation metrics and visual insights from the training process.

---

## **License**
This project is open-source and licensed under the **MIT License**. Refer to the [LICENSE](LICENSE) file for detailed terms.

---
