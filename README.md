# Talaba Imtihon Natijasini Bashorat Qilish (AI Loyihasi)

Bu loyiha sun'iy intellekt yordamida talabaning imtihondan o'tishi (Pass)
yoki yiqilishini (Fail) oldindan bashorat qiladi. Maqsad — o'qituvchiga
zaif talabalarni erta aniqlashga yordam berish.

## Loyiha haqida
- **Soha:** Ta'lim
- **Model turi:** Classification (Pass / Fail)
- **Vosita:** KNIME Analytics Platform
- **Ma'lumot:** Kaggle — Students Performance in Exams (1000 talaba)

## Ishlatilgan modellar
- Logistic Regression — aniqlik: 74%
- Random Forest — aniqlik: 74%

## Bosqichlar
1. Ma'lumotni o'qish (CSV Reader)
2. O'rtacha ball ustunini yasash (Math Formula)
3. Pass/Fail ustunini yasash (Rule Engine)
4. Ma'lumotni 80/20 ga bo'lish (Table Partitioner)
5. Modelni o'rgatish va bashorat qilish (Learner + Predictor)
6. Natijani baholash (Scorer)

## Xulosa
Model 74% aniqlikka erishdi. Umumiy bashoratda yaxshi ishlaydi, lekin
ma'lumot muvozanatsizligi sababli zaif talabalarni topishda kuchsizroq.
Yechim o'qituvchi uchun yordamchi vosita sifatida tavsiya etiladi.
