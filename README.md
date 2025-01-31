---

# 🌍 Global Terrorism Data Visualization Dashboard

![Dashboard Screenshot](global%20terrorist.png)


## 📖 Overview

The **Global Terrorism Data Visualization Dashboard** is an interactive tool designed to analyze and visualize data from the **Global Terrorism Database (GTD)** spanning from **1970 to 2017**. This dashboard provides insights into terrorist activities, helping researchers, policymakers, and the general public understand patterns and trends across different regions, countries, and years.

---

## ✨ Key Features

### 🗺️ **Interactive Heatmap**
- Visualizes the density and frequency of terrorist attacks worldwide.
- Zoom in and out for detailed geographic analysis.
- Colors represent the intensity of attacks, making it easy to identify hotspots.

### 🎚️ **Dynamic Filters**
- **Region Selection**: Focus on specific regions like South Asia, Middle East, etc.
- **Country Selection**: Analyze individual countries.
- **Year Range Slider**: Adjust the timeline to see trends over custom time periods.

### 📊 **Bar Chart Analysis**
- Displays trends in the number of attacks and deaths over selected years.
- Clear comparative visuals to understand peaks in activity and casualties.

### 🥧 **Pie Chart Summary**
- Summarizes **total attacks**, **deaths**, and **wounded** in an easy-to-digest format.
- Perfect for quick overviews and impactful presentations.

---

## 🛠️ Technologies Used

| Technology        | Purpose                                         |
|--------------------|-------------------------------------------------|
| **Python Dash**    | For building the interactive web application.  |
| **Plotly**         | For creating visually appealing charts.        |
| **GeoJSON**        | To render geographic data for heatmaps.        |
| **GTD Dataset**    | Primary data source (1970–2017).               |

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/prof2022/global-Terrorism.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application locally:
   ```bash
   python app.py
   ```

4. Open your browser and access:
   ```
   http://127.0.0.1:9001
   ```

---



## 🌟 Impact of the Project

- **Informed Policy Making**: Provides actionable insights for governments to combat terrorism effectively.
- **Research Support**: Aids researchers in analyzing historical trends and causes of terrorism.
- **Public Awareness**: Raises awareness of the impacts of terrorism through accessible and interactive data.

---

## 🔍 Recommendations

1. **Integrate Predictive Models**: Add machine learning algorithms to predict future trends in terrorism.
2. **Expand Dataset**: Incorporate recent data (post-2017) for more up-to-date insights.
3. **User Authentication**: Secure the dashboard by adding user login and session tracking.
4. **Export Functionality**: Allow users to download visualizations and data for offline use.
---

