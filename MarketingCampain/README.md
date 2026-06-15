# 📊 Marketing Campaign Dashboard

---

## 📁 Cấu trúc file

```              
├── MarketingCampagin
│   ├── README.md               
│   └── image.png
│   └── MarketingCampagine.pbix
│   └── Marketing_Campagine_dataset.xlsx                       

```

---

## 🗂️ Mô tả Dataset

**File:** `Marketing_Campagine_dataset.xlsx` — Sheet `marketing`  
**Số dòng:** 1.000 campaigns | **Thời gian:** 12/11/2024 – 09/02/2025

| Cột | Kiểu dữ liệu | Mô tả |
|-----|-------------|-------|
| `Campaign ID` | String 
| `Product Name` | String 
| `Category` | String 
| `Campaign Date` | Date 
| `Marketing Channel` | String 
| `Ad Spend (INR)` | Float 
| `Impressions` | Integer 
| `Clicks` | Integer 
| `Conversions` | Integer 
| `Revenue (INR)` | Float 
| `ROI` | Float | Return on Investment (%) |
| `CPM` | Float | Cost per 1000 Impressions |

---

## 📈 KPIs Tổng Quan

| Chỉ số | Giá trị |
|--------|---------|
| Total Ad Spend | ₹2.42M |
| Total Revenue | ₹344M |
| ROAS | 143x |
| CTR | 5.09% |
| Conversion Rate | 9.81% |
| Total Impressions | 242M |
| Total Clicks | 12M |
| Total Conversions | 1M |
| CPM trung bình | ₹10 |

---

## 🔍 Key Insights

### Hiệu suất theo kênh
```
→ Instagram Ads** có cost per conversion thấp nhất và ROAS cao nhất. **Influencer Marketing** dẫn đầu về avg ROI.
```
---

### Hiệu suất theo danh mục
```
→ Household** có ROAS cao nhất. **Personal Care** có avg ROI cao nhưng ROAS thấp — cần xem lại chiến lược upsell.
```
---

### Combo kênh × danh mục hiệu quả nhất (Avg ROI)

| Kênh | Danh mục | 
|------|----------|
| Instagram Ads | Household 
| Referral | Beverages 
| Referral | Personal Care 
| Google Ads | Personal Care 
| Email Campaign | Snacks 
```
→ Nên ưu tiên scale budget** cho các combo này.
```
---

## 📝 Ghi chú

- Unit: **INR (Rupee India)**
- Tools: **Power BI Desktop**
