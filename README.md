# Global Arms Trade Network Analysis
A geopolitical analysis of the global arms trade network using **SIPRI (Stockholm International Peace Research Institute)** data standards. This project implements advanced graph theory algorithms to map nations functioning as military power centers (*authorities*) and primary distribution connectors (*hubs*).

*This project serves as a Network Science case study to identify dominant state actors within the international defense ecosystem.*

## 📝 Project Description
This project models arms trade between nations as a directed graph, where suppliers and recipients are nodes, and transactions are edges. By utilizing the **HITS (Hubs and Authorities) algorithm**, the analysis successfully predicts global military leaders and how alliances are formed based on defense logistics flow.

## ✨ Key Features
- **Geopolitical Graph Modeling**: Representation of bilateral state relations as a complex network.
- **HITS Algorithm Implementation**: Distinguishing roles into *Authorities* (main power centers/targets) and *Hubs* (key connectors/distributors).
- **Centrality-Based Prediction**: Identifying camp leaders (e.g., USA, Ukraine, Saudi Arabia) based on military authority scores.
- **Top Actor Analysis**: Automated extraction of the top 5 most influential nations in the global arms trade network.

## 🛠️ Tech Stack & Implementation
- **Network Science**: NetworkX (for graph processing and HITS algorithm).
- **Data Manipulation**: Pandas (for SIPRI dataset cleaning).
- **Programming Language**: Python 3.x.
- **Environment**: Google Colab.

## 📊 Methodology
* **Data Preparation**: Transforming global arms transaction data (TIV - *Trend Indicator Value*) into a structured **adjacency list** format suitable for graph modeling.
* **Authority Analysis**: Calculating **Authority Scores** to identify nations with the highest military influence, specifically those serving as major technological hubs or primary acquisition centers.
* **Hub Analysis**: Identifying key state actors that play a pivotal role in **facilitating arms distribution** across various geopolitical regions.
* **Insight Generation**: Translating algorithmic scores into meaningful **geopolitical narratives** that reflect current global security dynamics and military alliances.

***

# Global Arms Trade Network Analysis
Analisis struktur geopolitik dunia melalui jaringan pengiriman senjata global menggunakan standar data **SIPRI (Stockholm International Peace Research Institute)**. Proyek ini mengimplementasikan algoritma teori graf canggih untuk memetakan negara-negara yang berfungsi sebagai pusat kekuatan militer (*authorities*) dan penghubung distribusi (*hubs*).

*Proyek ini merupakan studi kasus Analisis Jejaring (Network Science) untuk mengidentifikasi dominasi aktor negara dalam ekosistem pertahanan internasional.*

## 📝 Project Description
Proyek ini memodelkan perdagangan senjata antarnegara sebagai sebuah graf berarah (*directed graph*), di mana negara pengirim dan penerima adalah *nodes*, dan transaksi senjata adalah *edges*. Dengan menggunakan algoritma **HITS (Hubs and Authorities)**, analisis ini berhasil memprediksi pemimpin kubu kekuatan militer global dan bagaimana aliansi terbentuk berdasarkan arus logistik pertahanan.

## ✨ Key Features
- **Geopolitical Graph Modeling**: Representasi hubungan bilateral antar negara dalam bentuk jaringan kompleks.
- **HITS Algorithm Implementation**: Pemisahan peran negara menjadi *Authorities* (pusat kekuatan/tujuan utama) dan *Hubs* (penghubung/distributor utama).
- **Centrality-Based Prediction**: Mengidentifikasi negara pemimpin kubu (seperti Amerika Serikat, Ukraina, Arab Saudi) berdasarkan skor otoritas militer.
- **Top Actor Analysis**: Ekstraksi otomatis 5 negara paling berpengaruh dalam jaringan perdagangan senjata global.
- **Network Metrics**: Evaluasi struktur jaringan untuk memahami bagaimana stabilitas atau konflik dapat memengaruhi arus distribusi.

## 📊 Methodology
- **Data Preparation**: Mengolah data transaksi senjata dunia (TIV - *Trend Indicator Value*) menjadi format *adjacency list*.
- **Authority Analysis**: Menghitung skor otoritas untuk menentukan negara mana yang memiliki pengaruh militer terbesar sebagai penerima/pusat teknologi.
- **Hub Analysis**: Menentukan aktor yang berperan penting dalam memfasilitasi distribusi senjata ke berbagai wilayah.
- **Insight Generation**: Menginterpretasikan skor algoritma menjadi narasi geopolitik yang relevan dengan kondisi dunia saat ini.
