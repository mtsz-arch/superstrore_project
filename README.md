# 📊 Analiza sprzedaży i rentowności firmy e-commerce

Analiza danych sprzedażowych firmy **SuperStore** obejmująca czyszczenie danych, eksploracyjną analizę danych (EDA), feature engineering oraz budowę interaktywnego dashboardu w Power BI.

---

## Cele projektu

-  Analiza trendów sprzedażowych i rentowności  
- Segmentacja geograficzna i rynkowa  
- Profilowanie klientów według zachowań zakupowych  
- Optymalizacja procesów wysyłki  
- Stworzenie interaktywnego dashboardu do monitorowania KPI  

---

## 🛠️ Technologie

### Python & Biblioteki

- **pandas** – manipulacja i analiza danych  
- **matplotlib** – wizualizacja danych  
- **NumPy** – operacje numeryczne  
- **Google Colab** – środowisko deweloperskie  

### Business Intelligence

- **Power BI** – interaktywne dashboardy i raporty  

---

##  1. Przygotowanie danych

- Import i walidacja danych ze źródła `SuperStoreOrders.csv`
 <img width="1915" height="810" alt="obraz" src="https://github.com/user-attachments/assets/12710995-d6f9-41b7-ba5d-5ae74ad18226" />

- Obsługa brakujących wartości  
- Konwersja typów danych (numeryczne, kategoryczne, daty)  
- Parsowanie dat w formacie `dd/mm/yyyy`  
- Standaryzacja formatów liczbowych (obsługa separatorów tysięcznych)  

---

## ⚙️ 2. Feature Engineering

### Nowe zmienne analityczne:

- `order_year` – rok zamówienia  
- `order_month` – miesiąc zamówienia  
- `order_quarter` – kwartał zamówienia  

### Dodatkowe metryki biznesowe

---

## 🔍 3. Przeprowadzone analizy

### 📈 Analiza sprzedaży i zyskowności

- Identyfikacja produktów i kategorii o najwyższej sprzedaży  
- Analiza marż i rentowności  
- Wykrywanie produktów stratnych  

### 🌍 Segmentacja geograficzna

- Podział na regiony i rynki  
- Analiza wydajności według kraju  
- Mapowanie geograficzne sprzedaży  

### ⏱️ Analiza czasowa

- Trendy sprzedażowe w czasie  
- Sezonowość sprzedaży  
- Analiza wzorców zakupowych  

### 🚚 Optymalizacja wysyłki

- Średnie czasy dostawy według metody wysyłki  
- Analiza kosztów wysyłki  
- Priorytetyzacja zamówień  

### 👥 Segmentacja klientów

- Podział na segmenty (*Consumer, Corporate, Home Office*)  
- Analiza zachowań zakupowych  
- Wartość życiowa klienta (CLV)  

### 🔗 Analiza korelacji

- Badanie zależności między zmiennymi  
- Identyfikacja kluczowych czynników wpływających na zysk  
- Analiza wpływu rabatów na rentowność  

---

## 📊 Wizualizacje

Dashboard w **Power BI** zawiera:

- 📉 Trendy sprzedażowe i zyskowności w czasie  
- 🗺️ Mapy geograficzne wydajności sprzedaży  
- 📊 Wykresy porównawcze produktów i kategorii  
- 🎯 KPI i metryki biznesowe  
- 🔍 Interaktywne filtry i slicery  

---

## 🧠 Wyniki – kluczowe insighty

### 💰 Rentowność produktów

- Identyfikacja kategorii o najwyższej marży  
- Wykrycie produktów generujących straty  

### 🌍 Segmentacja geograficzna

- Najlepiej performujące regiony  
- Obszary wymagające dodatkowej uwagi  

### ⚙️ Optymalizacja procesów

- Rekomendacje dotyczące metod wysyłki  
- Usprawnienie obsługi zamówień priorytetowych  

### 👥 Profile klientów

- Charakterystyka segmentów klientów  
- Wzorce zakupowe według grup  
