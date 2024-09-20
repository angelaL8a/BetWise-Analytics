![ViewCount](https://views.whatilearened.today/views/github/angelaL8a/BetWise-Analytics.svg?cache=remove)
![GitHub top language](https://img.shields.io/github/languages/top/angelaL8a/BetWise-Analytics?style=flat)
![GitHub language count](https://img.shields.io/github/languages/count/angelaL8a/BetWise-Analytics?style=flat)

# 🎲 BetWise: Data Pipeline & Analytics Project 💡  
<img src="https://github.com/angelaL8a/BetWise-Analytics/blob/main/betwise.gif" alt="Peak Betting Hours" width="100%"/>  

Welcome to the **BetWise** repository! This project encompasses the design and implementation of a robust **Data Pipeline** for handling large-scale analytics and **Data Analytics** focusing on sports betting trends across multiple websites. The repository is structured in two key stages:

---

## 🚀 Project Overview


### 📁 Stage 1: Data Pipeline Design 🏗️

In this stage, we design and implement a data pipeline to process customer information across multiple locations. The pipeline automates the **ETL/ELT process** to facilitate seamless data transfer from the **Operations Center** to the **Analytics Center**.

**Scenario**:  
A new customer signed a contract and requires us to process their data and perform analytics to deliver valuable business insights. The analytics team has no direct access to the Operations Center, and the data must be replicated daily in **batch mode** using a custom API. The pipeline handles daily transfers of high-volume transactional data, ensuring secure and scalable processing.

🔹 **Pipeline Flow**: Data moves from Location 1 (Operations Center) to Location 2 (Analytics Center) via a secured API that allows pulling 5,000 records per call. The pipeline is designed to automate this flow and ensure data integrity.  
🔹 **Technologies Used**: AWS for cloud infrastructure, custom ETL/ELT strategies, secured data replication protocols.  



### 📁 Stage 2: Data Analytics 📊

This stage focuses on **Data Analytics** for a client in the sports betting industry. The analysis was conducted on a dataset containing transaction details, including player bets, odds, outcomes, and more.

#### **Key Insights**:

**High Proportion of Losses in Live Bets**  
<img src="https://github.com/angelaL8a/BetWise-Analytics/blob/main/Stage_2_Data_Analytics/assets/PL1.png" alt="Players Bet Type Preferences" width="600"/>  

**Impact of Betting Odds on Outcomes**   
<img src="https://github.com/angelaL8a/BetWise-Analytics/blob/main/Stage_2_Data_Analytics/assets/PL2.png" alt="Betting Odds Impact" width="600"/>  

**Consistent Currency Usage**  
<img src="https://github.com/angelaL8a/BetWise-Analytics/blob/main/Stage_2_Data_Analytics/assets/PL3.png" alt="Currency Distribution" width="600"/>  

**Player Preferences in Bet Types**  
<img src="https://github.com/angelaL8a/BetWise-Analytics/blob/main/Stage_2_Data_Analytics/assets/PL4.png" alt="Preferences in Bet Types" width="600"/>  

**Peak Betting Hours**  
<img src="https://github.com/angelaL8a/BetWise-Analytics/blob/main/Stage_2_Data_Analytics/assets/PL5.png" alt="Peak Betting Hours" width="600"/>  

---

## 📂 Repository Structure

The repository is divided into two main stages:

```
└── 📁betWork
    └── 📁Stage_1_Data_Pipeline_Design
        └── 📁assets
            └── data_pipeline_architecture.png  # Pipeline architecture diagram
            └── data_pipeline_diagram.png       # Pipeline process flow
        └── 📁docs
            └── Stage_1_Case_1.md               # Problem statement for Stage 1
            └── stage1_pipeline_solution.pdf    # Full solution documentation in PDF
    └── 📁Stage_2_Data_Analytics
        └── 📁assets
            └── PL1.png                         # Insight #1: Visualization
            └── PL2.png                         # Insight #2: Visualization
            └── PL3.png                         # Insight #3: Visualization
            └── PL4.png                         # Insight #4: Visualization
            └── PL5.png                         # Insight #5: Visualization
        └── 📁docs
            └── Stage_2_Case_2.md               # Problem statement for Stage 2
        └── 📁src
            └── data.csv                        # Raw betting data for analysis
            └── data.zip                        # Compressed data for faster access
            └── Stage_2_Case_2_Betting_Data_Analysis_PHP.pdf  # Full analysis report in PDF
            └── Stage_2_Case_2_Betting_Data_Analysis.ipynb    # Jupyter Notebook with all code and visualizations
    └── README.md                                # You're here! 😊
```

---

## 🛠️ Technologies & Tools Used

- **Cloud Platform**: AWS (preferred)
- **Programming Languages**: Python (for Data Analytics).
- **Tools**: Jupyter Notebooks & Plotly.

---

## 🚧 How to Use this Repository

1. **Stage 1: Data Pipeline Design**

   - **Docs**: Navigate to the `docs` folder inside `Stage_1_Data_Pipeline_Design` to find the problem statement (`Stage_1_Case_1.md`) and full solution (`stage1_pipeline_solution.pdf`).
   - **Visuals**: Explore the pipeline architecture and process flow diagrams located in the `assets` folder:
     - `data_pipeline_architecture.png`: Architecture diagram
     - `data_pipeline_diagram.png`: Process flow diagram

2. **Stage 2: Data Analytics**
   - **Source Code**: Run the Jupyter notebook (`Stage_2_Case_2_Betting_Data_Analysis.ipynb`) in the `src` folder to reproduce the analysis and insights.
   - **Data**: The raw data for analysis is provided as `data.csv`, and a compressed version is available as `data.zip`.
   - **Docs**: Review the problem statement (`Stage_2_Case_2.md`) located in the `docs` folder for Stage 2.
   - **Analysis Report PHP**: A full analysis report PHP is also provided as `Stage_2_Case_2_Betting_Data_Analysis_PHP.pdf`.
   - **Visuals**: View the insights visualizations in the `assets` folder:
     - `PL1.png` to `PL5.png`: Graphical representations of key insights.

---

## 🏆 Key Features

- 📈 **Detailed Data Analytics**: Advanced analysis of player behavior, betting outcomes, and market trends.
- 🔄 **Automated Data Pipelines**: Efficient and secure ETL/ELT processes that streamline data replication.
- 🎨 **Beautiful Visualizations**: Eye-catching, interactive plots to convey insights clearly and engagingly.
