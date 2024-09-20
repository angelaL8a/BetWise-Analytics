# Case 2: Sports Betting Data Analytics 🏅

## Business Case

One of our clients operates a **sports betting business** and manages multiple brands (websites) for their players across various locations. The dataset in the **"Raw Data"** tab contains detailed information about transactions (bets) made by players across multiple matches, including:

- 🏷️ **Bet Status**: Won, Lost, Draw
- 💰 **Stake Amount**: The amount placed for each bet
- 🎲 **Bet Type**: Different types of bets (e.g., Over/Under, Handicap)
- 🎯 **Odds**: The odds for each bet

## Assignment 📝

1. **Find the total player's stake in SGD** 💵.
2. Based on your observations of the data, share **5 or more insights** 📊 you have discovered.
3. **Predict the Actual Stake** 🎯 for the English Premier League (EPL) of each currency for the **next week**, using this data. Please provide your **assumptions and explanations**.
4. **Provide one suggestion** 🚀 on which metric in the dataset we should focus on to improve the **Player's Actual Stake** based on this dataset. Make sure to explain your reasoning and assumptions.

---

### Important Notes 📝

- Each **Transaction ID** is unique 🔑.
- Only the following bet statuses are considered valid: **Won, Lost, Draw**. Other statuses such as **D.L (danger ball)** or **VOID** are not valid and should be rejected 🚫.
- Status **VOID** refers to values in the local currency 🌍.
- **0**: Non-Live Matches, **1**: Live Matches 🕒.
- **Bet Types** 🏟️:
  - **h**: Home Team 🏠
  - **a**: Away Team 🚶‍♂️
  - **1**: Home Team Win 🏆
  - **X**: Draw 🤝
  - **2**: Away Team Win ⚽
- Example: **Betteam: h** and **Bettype: 3** means a bet on **Over**.

  - **1**: Handicap
  - **2**: Odd/Even
  - **3**: Over/Under
  - **4**: Correct Score
  - **5**: 1X2
  - **6**: Total Goals
  - **7**: First Half Handicap
  - **8**: First Half 1X2
  - **9**: First Half Over/Under

- Example: **Betteam: 2** and **Bettype: 5** refers to a bet placed on the **Away team** (if the player wins the bet) 🚀.

### Leagues Included 📅

- **3**: English Premier League 🇬🇧
- **4**: Italy Serie A 🇮🇹
- **5**: Germany Bundesliga 🇩🇪
- **6**: Spain La Liga 🇪🇸
- **8**: France Ligue 1 🇫🇷
- **13**: Represents one Website ID and indicates one customer 🔗.

---

### Submission Guidelines 📤

- Please prepare your answers using any relevant software (**Python**, **Excel**, etc.) 🖥️.
- Submit your answers in **PDF format** 📄.
- Provide **clear explanations** of your thought process for the questions above 💡.
