 📌 Overview  
This project analyzes **marketing campaign data** to find insights that help reduce **Cost per Acquisition (CPA)**. The main goal is to cut CPA by **15% in the next quarter** while keeping or increasing total conversions.  

---

# 📂 Project Structure  
```
├── campaign_data.csv                 # Cleaned dataset
├── marketing_campaign_data_messy.csv # Raw dataset
├── Marketing_Campaign_Project.ipynb  # Jupyter Notebook with analysis
├── README.md                         # Project documentation
```

---

# 📊 Dataset  
The dataset includes:  
- **Campaign Name**  
- **Channel** (Facebook, TikTok, Instagram, Email, etc.)  
- **Spend** (money spent on ads)  
- **Impressions** (how many people saw the ad)  
- **Clicks** (how many people clicked)  
- **Conversions** (how many people bought or signed up)  
- **Dates** (start and end of campaigns)  

---

# 🔍 Methodology  
1. **Data Cleaning**  
   - Fixed messy column names and channel names  
   - Removed invalid dates and duplicates  
   - Handled missing values  

2. **Exploratory Data Analysis (EDA)**  
   - Checked active vs inactive campaigns  
   - Compared conversions and impressions by channel and campaign  
   - Calculated key metrics: CTR, CPA, CPC, Conversion Rate  

3. **Red Flag Analysis**  
   - Found campaigns with **zero conversions** (high spend but no results)  
   - Highlighted wasted spend and possible funnel issues  

4. **Target CPA Analysis**  
   - Calculated current average CPA  
   - Set target CPA (15% lower)  
   - Compared campaigns below vs above target  

---

# 📊 Key Insights  
- Average campaign reach: ~49,000 impressions  
- Average clicks: ~1,500 (CTR ~3%)  
- Average conversions: ~188 (conversion rate ~12%)  
- Average CPA: ~11.6 (above target ~9.8)  
- Some campaigns are efficient (CPA ~2.6), others wasteful (CPA ~41.7)  
- Several campaigns spent thousands but had **zero conversions**  

👉 In short: campaigns get attention, but struggle to turn it into sales.  

---

# ✅ Recommendations  
- **Pause or fix zero-conversion campaigns**  
- **Reallocate budget** to campaigns below target CPA  
- **Audit landing pages and tracking** for funnel issues  
- **Test new creatives/targeting** for mid-performing campaigns  
- **Scale efficient campaigns** to maximize ROI  

---
#📊 Visualizations
- Here are some visualizations from the project:
1)<img width="831" height="537" alt="872b6cff-4276-4de2-9aee-176607de6b65" src="https://github.com/user-attachments/assets/dec33220-d24c-426f-9b7e-f7d4fa47d6cc" />
2)<img width="848" height="537" alt="1fdb5614-97db-45b0-9a5a-66fef32310ce" src="https://github.com/user-attachments/assets/bf74b92c-f690-4649-82b4-98d5f171fd25" />
3)<img width="409" height="389" alt="dd78d943-803d-4a1b-adc8-e2f158ea9d5a" src="https://github.com/user-attachments/assets/5b6eeb63-e5e2-4579-bc17-b349ef070008" />
4)<img width="599" height="455" alt="377392de-a966-451f-9e4d-92e872409feb" src="https://github.com/user-attachments/assets/d60173e6-af2c-484c-a3d0-5f372e560903" />
5)<img width="841" height="614" alt="49aecc7f-f5ba-463f-b6bc-c41a1b8d9fbb" src="https://github.com/user-attachments/assets/4e67c3e2-ce19-42cc-a44e-5d8484c55a72" />
6)<img width="831" height="614" alt="b5512b87-ca26-4996-96a9-ac41c66d94c0" src="https://github.com/user-attachments/assets/6bdae402-a83e-46b8-8f70-3be0809579ab" />
7)<img width="831" height="614" alt="5211b74e-2f25-4554-a53d-d05044b33510" src="https://github.com/user-attachments/assets/27e18daf-0183-4b47-b845-1c2077313133" />
8)<img width="831" height="614" alt="5211b74e-2f25-4554-a53d-d05044b33510" src="https://github.com/user-attachments/assets/7aa919ec-d445-4dc3-a0e3-34f817e0ac69" />
9)<img width="524" height="418" alt="e9b5d9a1-8547-4f72-8cc9-a91770a4c62f" src="https://github.com/user-attachments/assets/29f5a432-1706-496e-8dd0-5294effef33d" />
10)<img width="831" height="614" alt="9d824171-a5ea-4720-be59-ba4116ce298e" src="https://github.com/user-attachments/assets/46322a47-fb46-48f4-a2a9-7fb58ffa3a78" />

# 🛠️ Technologies Used  
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn    
- Jupyter Notebook  

---

# 🏁 Conclusion  
Campaigns are **good at reaching people and driving clicks**, but weak at turning them into conversions. By cutting waste, focusing on efficient campaigns, and fixing funnel issues, CPA can realistically be reduced by **15% in the next quarter**.  

