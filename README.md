# 🎮 Video Game Sales Analysis

## 📊 Project Overview
This project analyzes a video game dataset sourced from Kaggle to extract meaningful insights about the global gaming industry. Using Python, various analytical techniques and visualizations were applied to understand trends in genres, regional sales, platform evolution, and factors influencing commercial success.

---

## 📁 Dataset
Source: https://www.kaggle.com/datasets/ghassenkhaled/video-games-data

The dataset includes:
- Game Name
- Platform
- Year of Release
- Genre
- Publisher
- Regional Sales (NA, EU, JP, Others)
- Global Sales
- Critic Score & User Score

---

## 🧠 Key Findings

---

### 🎯 1. Genre Analysis

- Action, Sports, and Shooter genres dominate global sales.
- Role-Playing Games (RPGs) also show strong performance, especially in specific regions.
- Racing and Fighting genres contribute less compared to top-performing genres.

📌 Insight:
> Fast-paced and competitive gameplay genres have the highest global demand.

---

### 🌍 2. Regional Market Distribution

- North America → **49.4%**
- Europe → **27.2%**
- Japan → **14.5%**
- Other regions → **8.9%**

📌 Insight:
> North America leads the global gaming market, followed by Europe, while Japan maintains a strong but niche presence.

---

### 🏢 3. Publisher Dominance

- Major contributors:
  - Nintendo
  - EA
  - Activision
  - Sony

📌 Insight:
> The gaming industry is dominated by companies primarily based in the USA, Japan, and Europe, indicating strong regional supply-demand ecosystems.

---

### ⭐ 4. Critic Score vs Global Sales

- Weak positive relationship observed.
- High critic scores do not guarantee high sales.

📌 Machine Learning Model:
- Model: Random Forest Regressor
- R² Score: **0.41**

📌 Insight:
> Sales are influenced more by external factors such as brand value, marketing, and audience engagement rather than critic scores alone.

---

### 🎮 5. Platform Evolution & Lifecycle

#### Gaming Eras:
- **1980s–1990s** → NES, SNES (Foundation era)
- **Late 1990s–2000s** → PlayStation, N64
- **2000s** → PS2, Xbox, GameCube
- **2010s** → PS3, PS4, Xbox 360, Xbox One

📌 Key Observations:
- Platforms follow a lifecycle: **Growth → Peak → Decline**
- Typical lifespan: **5–10 years**
- PS2 stands out as the most successful console (≈11 years dominance)

📌 Insight:
> Platform lifecycle plays a critical role in determining game success.

---

### 📉 6. Market Dynamics (Hits vs Flops)

- Only **~12% of games are successful ("hits")**
- Majority of games fail commercially

📌 Insight:
> The gaming industry follows a **high-risk, high-reward model**

---

### 🌍 7. Regional Genre Preferences

#### Western Markets (NA & EU):
- Action
- Shooter
- Sports

#### Japan:
- Role-Playing Games (RPGs)
- Platform games

📌 Insight:
> Gaming preferences are strongly influenced by cultural factors.

---

### ⏳ 8. Platform Longevity Analysis

- PC → ~30+ years
- DS → ~35 years (data anomaly but notable)
- PS2 → ~11 years
- Xbox 360 → ~11 years

📌 Insight:
> Platforms with strong ecosystems and adaptability tend to survive longer.

---

### 📱 9. Industry Shift

- Decline in exclusive console dominance
- Rise of:
  - Cross-platform gaming (PC + Console)
  - Mobile gaming
  - Digital distribution

📌 Insight:
> The industry is shifting toward a more **integrated and platform-independent ecosystem**

---

## 📊 Tools & Technologies Used

- Python 🐍
- Pandas (Data Processing)
- Matplotlib / Seaborn (Visualization)
- Scikit-learn (Machine Learning)

---

## 🏆 Final Conclusion

- The gaming market is driven by **genre popularity, regional preferences, and platform lifecycle**
- **Blockbuster games dominate revenue**, while most games fail
- **Critic scores alone are not strong predictors of success**
- **Cultural and technological factors** play a key role in shaping the industry

---

## 📌 Author

Sibankar Saha
