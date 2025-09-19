# Analytics Platform for Dallas Local News Publishers

## Project Overview
This research project focuses on building an **analytics platform** to help Dallas local news publishers better understand their audience and engagement patterns.  
Our team consisted of two researchers, one mentor, and one supporting engineer.  

The main goal was to leverage **RFV (Recency, Frequency, Volume) metrics** and additional user behavior data to provide actionable insights into how readers interact with the publisher’s content.


## Key Steps & Contributions

### 1. Understanding RFV Metrics
- **RFV metric** provides better insight into how people are engaging with the site. 
- Generated **descriptive statistics** for the RFV-related variables by using **Jupyter Notebook (`RFV Analytics Data.ipynb`)** .


### 2. Comparative User Behavior Analysis
Conducted multiple comparisons of user engagement, including:
- **Bounce vs. Non-bounce users**  
- **First-time vs. Returning visitors**  
- **Dallas-based vs. Non-Dallas users**  
- Metrics considered: Bounce rate, Time spent, Return rate, Device usage, Referral source and so on.


### 3. Predictive Modeling
- Built a **decision tree** to predict whether a user would return for another session.  
  - Results available in **`Modeling.ipynb`**.  
- Expanded dataset and developed a **refined decision tree** for higher prediction accuracy.  
  - Results available in **`event data.ipynb`**.


### 4. Site Path Visualization
- Constructed a **site path analysis** to illustrate the sequence of articles each user visited on the news site.  
- This visualization helped uncover **user navigation patterns** and content flow.


## Repository Structure
- `RFV Analytics Data.ipynb` → Descriptive statistics and RFV metric analysis  
- `Modeling.ipynb` → Initial decision tree modeling for user return prediction  
- `event data.ipynb` → Enhanced modeling with additional data for improved accuracy  
- `site path visualization` → User journey mapping through visited articles  


##  Outcomes
- Developed an **analytics platform prototype** that allows local publishers to:
  - Measure **user engagement** via RFV metrics  
  - Compare **behavioral patterns** across different user groups  
  - Predict **user return probability** with machine learning models  
  - Visualize **site navigation paths** for content optimization  


## Tech Stack
- **Python** (Pandas, Scikit-learn, Matplotlib, Seaborn)  
- **Jupyter Notebook**  
- **Decision Tree Models**  
- **Visualization tools** for path analysis  


## Notes
This repository serves as a **research project archive**.  
Future improvements may include:
- Testing additional ML models (Random Forest, XGBoost)  
- Automating dashboard creation for publishers  
- Integrating real-time user data  

