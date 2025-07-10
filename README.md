# IST374-Project

## Proje Özeti / Project Summary

Bu proje kapsamında, gerçek hayattan elde edilen finansal veriler kullanılarak bir stokastik süreç tanımlanmış ve bu süreç üzerinde Markov zinciri analizi gerçekleştirilmiştir. /  
In this project, a stochastic process was defined using real-world financial data, and Markov chain analysis was applied to the process.

---

## Kapsanan Konular / Covered Topics

- Gerçek veri seti ile stokastik süreç tanımlama / Defining a stochastic process using real data  
- Durum uzayı ve zaman parametresinin belirlenmesi / Specification of state space and time parameter  
- Markov zinciri için bir-adım geçiş olasılık matrisinin oluşturulması / Construction of one-step transition matrix for a Markov chain  
- Geçiş diyagramlarının çizilmesi ve yorumlanması / Drawing and interpreting transition diagrams  
- P³, P¹⁰, P¹⁰⁰ matrislerinin oluşturulması ve analizi / Computation and analysis of P³, P¹⁰, P¹⁰⁰ matrices  
- İndirgenebilirlik, kapalı küme, yutucu ve periyodik durumların belirlenmesi / Determination of reducibility, closed classes, absorbing and periodic states  
- Denge dağılımının varlığı ve yorumlanması / Existence and interpretation of stationary distribution  

---

## Kullanılan Veri / Data Used

- **Veri Kümesi / Dataset:** DoorDash Inc. ($DASH) hisse senedine ait kapanış fiyatları / Closing prices of DoorDash Inc. stock ($DASH)  
- **Zaman Aralığı / Time Period:** 4 Ocak 2021 – 4 Ocak 2024 (769 iş günü) / January 4, 2021 – January 4, 2024 (769 trading days)  
- **Kaynak / Source:** [Yahoo Finance](https://finance.yahoo.com)  

---

## Kullanılan Araçlar / Tools Used

- R
- R Markdown
- ggplot2, markovchain, tidyverse

