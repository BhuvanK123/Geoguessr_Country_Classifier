# GeoGuessr‑Inspired Country Classification  
*A Winter Break Machine Learning Project I made for fun*

## Overview  
This project started as something I wanted to do over winter break. Since I’ve always loved playing **GeoGuessr**, I thought it would be fun to explore how a machine learning model might approach the same kind of geographic reasoning that players use.

Instead of working with real images, I built a **synthetic dataset** that captures the kinds of clues you’d normally look for in Street View:  
- road markings  
- driving side  
- utility poles  
- bollards  
- signage  
- landscapes  
- license plate rules  

The goal was simple:  
**Can a model learn to guess the country from these clues alone?**

Turns out **Yes**. And it was surprisingly fascinating.

---

## Dataset  
- **200 rows**  
- **7 countries:** USA, Canada, UK, France, Brazil, Japan, Australia  
- **12 categorical features**  
- All data is **synthetic**, but based on realistic infrastructure patterns  
- Designed to mimic the logic of GeoGuessr without using real imagery  

---

## Model  
I trained a **Decision Tree Classifier** on the dataset using an 80/20 train‑test split.

### Results  
- **Accuracy:** ~80%  
- **Confusion Matrix:** Shows strong performance on countries with distinctive features  
- **Feature Importance:** The model relied heavily on driving side, road lines, and utility pole types, which is exactly what I look for when I play GeoGuessr  

Seeing the model latch onto the same clues I use as a player was one of the coolest parts of this project.

---

## What I Learned  
- How to design a structured dataset from scratch  
- How to encode categorical features for ML  
- How to interpret confusion matrices and feature importance  
- How geographic reasoning can be modeled without images  
- That synthetic data can still produce meaningful results  

---

## Why This Project Matters to Me  
This wasn’t just a school assignment or a random experiment.  
It was something I genuinely wanted to explore and a way to combine my interest in machine learning with a hobby I enjoy. Working on it over winter break also made it relaxing and fun.

It also gave me a new appreciation for how subtle geographic clues really are, and how much intuition goes into recognizing a place.

---

## Future Ideas  
- Add more countries  
- Add more features (vegetation, climate, road width, etc.)  
- Combine structured features with image embeddings  
- Build a small interactive demo  

---
