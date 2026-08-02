# Jeonju Urban Heat Island Map · Green Space Recommendation · Quiz Application 🏝
This mobile application analyzes **the Urban Heat Island (UHI) phenomenon in Jeonju City** and provides **urban heat island map visualization, nearby green space recommendations, and an educational quiz on heat island concepts.** The project aims to raise public awareness of urban heat issues while offering data-driven, location-based recommendations.
  
<img width="1920" height="1080" alt="슬라이드1" src="https://github.com/user-attachments/assets/7b5dc1d9-e2ef-4934-b258-13c553ffe022" />
<br/>
<br/>

## 📱 Key Features

### 1. Main Screen
- Requests current location permission
- Displays real-time temperature and heat index using the **Korea Meteorological Administration (KMA) API**
- Buttons to access:
  - Green space recommendation
  - Heat island quiz
- Displays **yearly Jeonju heat island maps** at the bottom
  
<img width="1920" height="1080" alt="슬라이드9" src="https://github.com/user-attachments/assets/23808260-c7f1-4c13-831e-f91b9a12ce63" />
<br/>
<br/>

### 2. Green Space Recommendation
- Recommends **Top 10 nearby parks** based on the user’s current location
- Ranking is computed using a **composite score**:
  - Distance
  - Area size
  - Available facilities
- Map markers:
  - 🟡 Top 3 parks
  - 🔴 Other recommended parks
  - 🔵 Selected park
- Provides:
  - Detailed information via list view
  - Navigation support
  
<img width="1920" height="1080" alt="슬라이드10" src="https://github.com/user-attachments/assets/eef5efa2-7b69-42f3-bd46-0b84b1ba98cc" />
<img width="1920" height="1080" alt="슬라이드11" src="https://github.com/user-attachments/assets/5292d7f0-dc4f-4b86-a829-d64ffb7db723" />
<img width="1920" height="1080" alt="슬라이드12" src="https://github.com/user-attachments/assets/5c9a0289-34e9-44f8-b763-b7d6241fbdb2" />
<br/>
<br/>

### 3. Jeonju Urban Heat Island Map
- Visualizes data from **2017 to 2021**
- Heat island index (UHI) represented by colored radius circles:
  - 🔴 Red: 80 or higher  
  - 🟠 Orange: 76 or higher  
  - 🟡 Yellow: below 76  
  - ⚪ Gray: no data
- Supports:
  - Year-by-year comparison
  - Region-specific information pop-ups
  
<img width="1920" height="1080" alt="슬라이드13" src="https://github.com/user-attachments/assets/a8cd9534-4122-4b39-81c6-a07ddadb6206" />
<br/>
<br/>

### 4. Urban Heat Island Knowledge Quiz
- Randomly generates quiz questions on execution
- Provides hint functionality
- Designed to improve public understanding of urban heat island phenomena
  
<img width="1920" height="1080" alt="슬라이드14" src="https://github.com/user-attachments/assets/dbf32c99-5ebe-4edf-8dcd-21f74d2c9985" />
<br/>
<br/>

## 🛠 Tech Stack
<img width="1920" height="1080" alt="슬라이드6" src="https://github.com/user-attachments/assets/bb02aebe-8e1a-4d93-a561-d249ab7a0ca3" />
<br/>
<br/>

## 👥 Team Roles
- **Jihyeon Kang**: Urban heat island quiz implementation  
- **Sehyun Kim**: Heat island map implementation, database & GitHub management, real-time temperature display  
- **Jeongmin Lim**: Main page development, UI design, presentation & pitching  
- **Junhee Jung**: Google Maps API integration  
- **Jaehyun Cha**: Green space recommendation algorithm
<br/>
<br/>
