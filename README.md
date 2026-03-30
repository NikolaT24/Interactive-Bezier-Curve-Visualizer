<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,50:243B55,100:0f2027&height=230&section=header&text=Bezier%20Curve%20Visualizer&fontSize=40&fontAlignY=35&fontColor=ffffff&animation=fadeIn&desc=Interactive%20De%20Casteljau%20Algorithm&descAlignY=55&descSize=18" />
</p>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=3000&color=00F5D4&center=true&vCenter=true&width=700&lines=Draw+Curves+With+Clicks;Watch+Math+Come+Alive;De+Casteljau+in+Real+Time;Geometry+Meets+Interaction" />

<br><br>

<img src="https://img.shields.io/badge/Canvas-Interactive-00F5D4?style=for-the-badge">
<img src="https://img.shields.io/badge/Algorithm-De%20Casteljau-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Tech-JavaScript-black?style=for-the-badge">

<br><br>

# 🎨 Bézier Curve Visualizer

<i>An interactive playground for exploring Bézier curves and the De Casteljau algorithm in real time.</i>

---

</div>

## ✨ Overview

This project transforms your browser into a **dynamic geometry canvas** where you can:

- Create control points  
- Manipulate them freely  
- Watch curves emerge in real time  

It’s not just drawing.  
It’s **watching mathematics unfold visually**.

---

## 🧠 The Idea

At the heart of this project lies the **De Casteljau algorithm** — a recursive interpolation process used to construct Bézier curves.

Instead of hiding the math, this app **reveals every step**:
- Intermediate points  
- Subdivision layers  
- Final curve formation  

---

## 🖱️ Interaction Guide

### 🎯 Controls

- **Left Click** → Add a control point  
- **Drag Point** → Move it dynamically  
- **Right Click** → Remove last point  
- **Slider (t)** → Adjust interpolation parameter  
- **Checkbox** → Toggle Bézier curve visibility  
- **Button** → Clear all points  

---

## 🎥 What You See

- 🔵 Control points  
- 🟣 Control polygon  
- 🟡 Intermediate interpolation layers  
- 🟢 Final Bézier curve  

Everything updates **in real time** as you interact.

---

## ⚙️ How It Works

### 🔹 Linear Interpolation
Each step blends points:

```js
x = p0.x + (p1.x - p0.x) * t
y = p0.y + (p1.y - p0.y) * t
