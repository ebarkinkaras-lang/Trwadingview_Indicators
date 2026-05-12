# 🤖 AI Trading Algorithms (Pine Script)

![TradingView](https://img.shields.io/badge/Platform-TradingView-blue?logo=tradingview)
![Pine Script](https://img.shields.io/badge/Language-Pine%20Script-orange)
![License](https://img.shields.io/badge/License-MIT-green)

> 🇹🇷 Türkçe | [🇬🇧 English](#-english) | [🇩🇪 Deutsch](#-deutsch)

Bu repository, profesyonel TradingView analizleri için geliştirilmiş iki güçlü yapay zeka ve algoritmik ticaret göstergesini içerir.

> ⚠️ **Sorumluluk Reddi:** Bu proje kazanç garantisi vermez. Yalnızca piyasa tahminine yardımcı olmak amacıyla üretilmiş bir yardımcı araçtır. Yatırım tavsiyesi değildir.

---

## 📌 İçindekiler
- [MC-Predict HullMA v2](#1-mc-predict-hullma-v2-with-zigzag-auto-fibonacci)
- [MACD DEMA Pro v2](#2-macd-dema-pro-v2)
- [Kurulum](#️-kurulum-tradingview)

---

## 1. MC-Predict HullMA v2 (with ZigZag Auto Fibonacci)
**Dosya:** `MC-Predict_HullMA_v2.pine`

Klasik Hull Moving Average (HMA) göstergesinin makine öğrenmesi (kNN) ve gelişmiş filtrelerle donatılmış 2. versiyonudur.

| Özellik | Açıklama |
|---|---|
| **kNN (K-Nearest Neighbors)** | Tarihsel RSI, MACD ve Bollinger verilerini tarayarak anlık fiyatın yönünü tahmin eder (Z-Score normalizasyonu içerir). |
| **ADX Trend Filtresi** | Yatay piyasalardaki sahte (fakeout) sinyalleri filtreler. Sadece trend olan piyasalarda "Güçlü Al/Sat" üretir. |
| **ZigZag Auto Fibonacci Extension** | Endüstri standardı ZigZag algoritması ile A-B-C pivot noktalarını tespit eder ve Fib 1.0, 1.618, 2.618 seviyelerini otomatik çizer. |
| **Multi-Timeframe (MTF)** | Günlük grafikteyken haftalık trendi tek bir `request.security` çağrısıyla getirir. |

---

## 2. MACD DEMA Pro v2
**Dosya:** `MACD_DEMA_Pro_v2.pine`

Geleneksel MACD'nin "gecikme" (lag) sorununu ortadan kaldırmak için DEMA (Double Exponential Moving Average) kullanılarak sıfırdan yazılmış profesyonel bir osilatördür.

---

## ⚙️ Kurulum (TradingView)

1. İlgili `.pine` dosyasını açın ve içindeki kodu kopyalayın.
2. TradingView'da alt panelden **Pine Editör**'ü açın.
3. İçindeki her şeyi silip kodu yapıştırın.
4. **"Grafiğe Ekle"** butonuna tıklayın.

---
---

## 🇬🇧 English

This repository contains two powerful AI and algorithmic trading indicators developed for professional TradingView analysis.

> ⚠️ **Disclaimer:** This project does not guarantee gains. It is produced solely as a helping tool for market prediction. Not investment advice.

---

## 1. MC-Predict HullMA v2 (with ZigZag Auto Fibonacci)
**File:** `MC-Predict_HullMA_v2.pine`

The second version of the classic Hull Moving Average (HMA) indicator, enhanced with machine learning (kNN) and advanced filters.

| Feature | Description |
|---|---|
| **kNN (K-Nearest Neighbors)** | Scans historical RSI, MACD, and Bollinger data to predict current price direction (includes Z-Score normalization). |
| **ADX Trend Filter** | Filters out fakeout signals in sideways markets. Generates "Strong Buy/Sell" only in trending markets. |
| **ZigZag Auto Fibonacci Extension** | Detects A-B-C pivot points using the industry-standard ZigZag algorithm and automatically draws Fib 1.0, 1.618, 2.618 levels. |
| **Multi-Timeframe (MTF)** | Fetches the weekly trend with a single `request.security` call while on the daily chart. |

---

## 2. MACD DEMA Pro v2
**File:** `MACD_DEMA_Pro_v2.pine`

A professional oscillator written from scratch using DEMA (Double Exponential Moving Average) to eliminate the lag problem of the traditional MACD.

---

## ⚙️ Installation (TradingView)

1. Open the relevant `.pine` file and copy the code.
2. Open the **Pine Editor** from the bottom panel in TradingView.
3. Delete everything inside and paste the code.
4. Click **"Add to Chart"**.

---
---

## 🇩🇪 Deutsch

Dieses Repository enthält zwei leistungsstarke KI- und algorithmische Handelsindikatoren für professionelle TradingView-Analysen.

> ⚠️ **Haftungsausschluss:** Dieses Projekt übernimmt keine Garantie für Gewinne. Es wurde ausschließlich als Hilfsmittel zur Marktvorhersage entwickelt. Keine Anlageberatung.

---

## 1. MC-Predict HullMA v2 (mit ZigZag Auto Fibonacci)
**Datei:** `MC-Predict_HullMA_v2.pine`

Die zweite Version des klassischen Hull Moving Average (HMA) Indikators, erweitert mit maschinellem Lernen (kNN) und fortgeschrittenen Filtern.

| Funktion | Beschreibung |
|---|---|
| **kNN (K-Nearest Neighbors)** | Durchsucht historische RSI-, MACD- und Bollinger-Daten zur Richtungsvorhersage (mit Z-Score-Normalisierung). |
| **ADX-Trendfilter** | Filtert Fakeout-Signale in Seitwärtsmärkten. Erzeugt „Starkes Kaufen/Verkaufen" nur in Trendmärkten. |
| **ZigZag Auto Fibonacci Extension** | Erkennt A-B-C-Pivotpunkte und zeichnet automatisch Fib 1,0 / 1,618 / 2,618 Levels ein. |
| **Multi-Timeframe (MTF)** | Ruft den Wochentrend mit einem einzigen `request.security`-Aufruf ab. |

---

## 2. MACD DEMA Pro v2
**Datei:** `MACD_DEMA_Pro_v2.pine`

Ein professioneller Oszillator, von Grund auf neu mit DEMA (Double Exponential Moving Average) entwickelt, um das Lag-Problem des traditionellen MACD zu beseitigen.

---

## ⚙️ Installation (TradingView)

1. Öffnen Sie die gewünschte `.pine`-Datei und kopieren Sie den Code.
2. Öffnen Sie den **Pine-Editor** über das untere Panel in TradingView.
3. Löschen Sie den gesamten Inhalt und fügen Sie den Code ein.
4. Klicken Sie auf **„Zum Chart hinzufügen"**.
