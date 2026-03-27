# 📱 EDA and Feature Engineering Project on Mobile Dataset

> Decoding mobile price trends — exploring specs, features, and pricing patterns through data-driven analysis.

---

## 📌 Table of Contents

- [📖 Project Overview](#-project-overview)
- [📂 Project Repository Structure](#-project-repository-structure)
- [📊 Dataset Information](#-dataset-information)
- [⚙️ Technologies Used](#️-technologies-used)
- [📈 EDA Highlights](#-eda-highlights)
- [🛠️ Feature Engineering Steps](#️-feature-engineering-steps)
- [🖼️ Visualizations](#️-visualizations)
- [🚀 How to Run](#-how-to-run)
- [🤝 Contributing](#-contributing)

---

## 📖 Project Overview

This project performs comprehensive **Exploratory Data Analysis (EDA)** and **Feature Engineering** on a **Mobile Prices Dataset**. With the smartphone market evolving rapidly, understanding what drives mobile pricing is both practically and analytically valuable.

Through this project, we investigate key hardware specifications — RAM, battery, camera, storage, and more — to uncover the features that most significantly influence a device's price range. The cleaned and engineered dataset is prepared for downstream machine learning classification or regression tasks.

---

## 📂 Project Repository Structure

```
EDA_and_Feature_Engineering_Project_on_Mobile_Dataset/
│
├── EDA and Feature Engineering Project on Mobile Dataset/
│   ├── EDA and Feature Engineering on Mobile Dataset.ipynb
│   ├── Mobile Prices.csv
│   └── README.md
│
└── Correlation Matrix Heatmap.png
```

---

## 📊 Dataset Information

- **Dataset Name:** `Mobile Prices.csv`
- **Domain:** Consumer Electronics / E-Commerce
- **Key Features Include:**

| Feature | Description |
|---------|-------------|
| `battery_power` | Total energy a battery can store (mAh) |
| `blue` | Has Bluetooth or not (boolean) |
| `clock_speed` | Speed of the microprocessor |
| `dual_sim` | Has dual SIM support or not (boolean) |
| `fc` | Front camera megapixels |
| `four_g` | Has 4G support or not (boolean) |
| `int_memory` | Internal memory in GB |
| `m_dep` | Mobile depth in cm |
| `mobile_wt` | Weight of the mobile phone |
| `n_cores` | Number of processor cores |
| `pc` | Primary camera megapixels |
| `px_height` | Pixel resolution height |
| `px_width` | Pixel resolution width |
| `ram` | Random Access Memory in MB |
| `sc_h` | Screen height in cm |
| `sc_w` | Screen width in cm |
| `talk_time` | Longest time a battery charge will last (hours) |
| `three_g` | Has 3G support or not (boolean) |
| `touch_screen` | Has touch screen or not (boolean) |
| `wifi` | Has WiFi or not (boolean) |
| `price_range` | Price range category (0=Low, 1=Medium, 2=High, 3=Very High) |

---

## ⚙️ Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 Python | Core programming language |
| 📊 Pandas & NumPy | Data manipulation and analysis |
| 📉 Matplotlib & Seaborn | Data visualization |
| 📓 Jupyter Notebook | Interactive development environment |

---

## 📈 EDA Highlights

- ✅ Analyzed the **distribution of mobile prices** across different price range categories
- ✅ Explored the **impact of RAM, battery, and camera** specs on price range
- ✅ Examined **correlation between all numerical features** using a heatmap
- ✅ Identified and treated **outliers** in hardware specification columns
- ✅ Investigated **connectivity features** (4G, 3G, WiFi, Bluetooth) and their relationship with pricing
- ✅ Compared **screen resolution and size** trends across price segments

---

## 🛠️ Feature Engineering Steps

- 🔄 Converted **boolean/binary features** into appropriate numerical formats
- 🧹 Handled **missing values** and data inconsistencies
- 📏 Applied **scaling and normalization** to continuous hardware specifications
- 🧪 Created **derived features** such as pixel density and screen area
- 🗂️ Encoded **categorical variables** for model compatibility
- 📊 Conducted **feature selection** to identify the most impactful predictors of price range

---

## 🖼️ Visualizations

### 🔥 Correlation Matrix Heatmap

This heatmap reveals the correlations between all numerical features in the dataset, helping identify which hardware specifications are most closely related to each other and to the target price range.

![Correlation Matrix Heatmap](https://raw.githubusercontent.com/AbhishekDhawan07/EDA_and_Feature_Engineering_Project_on_Mobile_Dataset/main/Correlation%20Matrix%20Heatmap.png)

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AbhishekDhawan07/EDA_and_Feature_Engineering_Project_on_Mobile_Dataset.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd "EDA and Feature Engineering Project on Mobile Dataset"
   ```

3. **Install required dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. **Launch the Jupyter Notebook:**
   ```bash
   jupyter notebook "EDA and Feature Engineering on Mobile Dataset.ipynb"
   ```

5. **Run all cells** to reproduce the full analysis and visualizations.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and available for educational and research purposes.

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐

Made with ❤️ by [Abhishek Dhawan](https://github.com/AbhishekDhawan07)

</div>
