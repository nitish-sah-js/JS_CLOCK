# 🕒 JS + CSS Analog Clock

A simple and elegant analog clock built using **HTML**, **CSS**, and **JavaScript**.  
It displays the current time with smoothly rotating hour, minute, and second hands.

---

## 🔍 Code Review

### Overview
The **HTML** defines the clock structure and hands,  
**CSS** styles it into a circular design with transitions, and  
**JavaScript** continuously updates the hand positions in real time.

### ✅ Strengths
- Clean and easy-to-understand code  
- Effective use of CSS `transform` and `transform-origin`  
- Visually appealing layout with subtle shadows and background  

### ⚙️ Possible Improvements
- Fix the “jump” when seconds reset from `59 → 0` (caused by CSS transition)  
- Animate minute and hour hands smoothly (continuous motion)  
- Consider using `requestAnimationFrame()` for smoother updates  
- Add tick marks or numbers for improved readability  

---

## 🚀 Features
- Real-time analog clock  
- Smooth CSS transitions  
- Centered, responsive layout  
- Simple and minimal UI  

---

## 🧠 How It Works
1. The JavaScript `Date()` object retrieves the current hour, minute, and second.  
2. Each hand’s rotation is calculated in degrees (`(time / max) * 360 + 90`).  
3. The rotation values are applied with CSS `transform: rotate()`.  
4. The `setInterval()` function updates the clock every second.  

---

## 📂 Usage
1. Download or clone this repository.  
2. Open `index.html` in your browser.  
3. The clock will start running automatically.  

